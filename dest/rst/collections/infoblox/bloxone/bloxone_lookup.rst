.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.15.0

.. Anchors

.. _ansible_collections.infoblox.bloxone.bloxone_lookup:

.. Anchors: short name for ansible.builtin

.. Title

infoblox.bloxone.bloxone lookup -- Query Infoblox BloxOne DDI objects
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This lookup plugin is part of the `infoblox.bloxone collection <https://galaxy.ansible.com/ui/repo/published/infoblox/bloxone/>`_ (version 2.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install infoblox.bloxone`.
    You need further requirements to be able to use this lookup plugin,
    see :ref:`Requirements <ansible_collections.infoblox.bloxone.bloxone_lookup_requirements>` for details.

    To use it in a playbook, specify: :code:`infoblox.bloxone.bloxone`.

.. version_added

.. rst-class:: ansible-version-added

New in infoblox.bloxone 1.1.0

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- Uses the BloxOne DDI REST API to fetch BloxOne specified objects. This lookup supports adding additional keywords to filter the return data and specify the desired set of returned fields.


.. Aliases


.. Requirements

.. _ansible_collections.infoblox.bloxone.bloxone_lookup_requirements:

Requirements
------------
The below requirements are needed on the local controller node that executes this lookup.

- requests




.. Terms

Terms
-----

.. tabularcolumns:: \X{1}{3}\X{2}{3}

.. list-table::
  :width: 100%
  :widths: auto
  :header-rows: 1
  :class: longtable ansible-option-table

  * - Parameter
    - Comments

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-_terms"></div>

      .. _ansible_collections.infoblox.bloxone.bloxone_lookup__parameter-_terms:

      .. rst-class:: ansible-option-title

      **Terms**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-_terms" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      The name of the object to return from BloxOne


      .. raw:: html

        </div>





.. Options

Keyword parameters
------------------

This describes keyword parameters of the lookup. These are the values ``key1=value1``, ``key2=value2`` and so on in the following
examples: ``lookup('infoblox.bloxone.bloxone', key1=value1, key2=value2, ...)`` and ``query('infoblox.bloxone.bloxone', key1=value1, key2=value2, ...)``

.. tabularcolumns:: \X{1}{3}\X{2}{3}

.. list-table::
  :width: 100%
  :widths: auto
  :header-rows: 1
  :class: longtable ansible-option-table

  * - Parameter
    - Comments

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-fields"></div>

      .. _ansible_collections.infoblox.bloxone.bloxone_lookup__parameter-fields:

      .. rst-class:: ansible-option-title

      **fields**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-fields" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      The list of field names to return for the specified object.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-filters"></div>

      .. _ansible_collections.infoblox.bloxone.bloxone_lookup__parameter-filters:

      .. rst-class:: ansible-option-title

      **filters**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-filters" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      a dict object that is used to filter the return objects


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-provider"></div>

      .. _ansible_collections.infoblox.bloxone.bloxone_lookup__parameter-provider:

      .. rst-class:: ansible-option-title

      **provider**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-provider" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      a dict object containing BloxOne host name and API key


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-tfilters"></div>

      .. _ansible_collections.infoblox.bloxone.bloxone_lookup__parameter-tfilters:

      .. rst-class:: ansible-option-title

      **tfilters**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-tfilters" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      a dict object that is used to filter the return objects based on tags


      .. raw:: html

        </div>


.. Attributes


.. Notes

Notes
-----

.. note::
   - When keyword and positional parameters are used together, positional parameters must be listed before keyword parameters:
     ``lookup('infoblox.bloxone.bloxone', term1, term2, key1=value1, key2=value2)`` and ``query('infoblox.bloxone.bloxone', term1, term2, key1=value1, key2=value2)``

.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    - name: fetch all IP Space objects
      ansible.builtin.set_fact:
        ip_space: "{{ lookup('bloxone', '/ipam/ipspace' , filters={'name': 'vsethia-ip-space'}, tfilters={'Tagname': '<value>'}, fields=['id', 'name', 'comment'] , provider={'host': '{{host}}', 'api_key': '{{api_key}}'}) }}"



.. Facts


.. Return values


..  Status (Presently only deprecated)


.. Authors

Authors
~~~~~~~

- Vedant Sethia (@vedantsethia)
- Chris Marrison (@ccmarris)


.. hint::
    Configuration entries for each entry type have a low to high priority order. For example, a variable that is lower in the list will override a variable that is higher up.

.. Extra links

Collection links
~~~~~~~~~~~~~~~~

.. ansible-links::

  - title: "Issue Tracker"
    url: "https://github.com/infobloxopen/bloxone-ansible/issues"
    external: true
  - title: "Repository (Sources)"
    url: "https://github.com/infobloxopen/bloxone-ansible"
    external: true


.. Parsing errors
