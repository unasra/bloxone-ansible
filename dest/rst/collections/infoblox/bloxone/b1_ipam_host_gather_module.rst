.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.15.0

.. Anchors

.. _ansible_collections.infoblox.bloxone.b1_ipam_host_gather_module:

.. Anchors: short name for ansible.builtin

.. Title

infoblox.bloxone.b1_ipam_host_gather module -- Gather IPAM host facts
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `infoblox.bloxone collection <https://galaxy.ansible.com/ui/repo/published/infoblox/bloxone/>`_ (version 2.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install infoblox.bloxone`.
    You need further requirements to be able to use this module,
    see :ref:`Requirements <ansible_collections.infoblox.bloxone.b1_ipam_host_gather_module_requirements>` for details.

    To use it in a playbook, specify: :code:`infoblox.bloxone.b1_ipam_host_gather`.

.. version_added


.. contents::
   :local:
   :depth: 1

.. Deprecated

DEPRECATED
----------
:Removed in: version 3.0.0
:Why: This module is deprecated and will be removed in version 3.0.0. Use :strong:`ERROR while parsing`\ : While parsing "M(ipam\_host\_info)" at index 69: Module name "ipam\_host\_info" is not a FQCN instead.
:Alternative: Use :strong:`ERROR while parsing`\ : While parsing "M(ipam\_host\_info)" at index 5: Module name "ipam\_host\_info" is not a FQCN instead.

Synopsis
--------

.. Description

- Gather facts about IPAM hosts in Infoblox BloxOne DDI. This module gathers facts of IPAM Hosts object using BloxOne REST APIs.


.. Aliases


.. Requirements

.. _ansible_collections.infoblox.bloxone.b1_ipam_host_gather_module_requirements:

Requirements
------------
The below requirements are needed on the host that executes this module.

- requests






.. Options

Parameters
----------

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
        <div class="ansibleOptionAnchor" id="parameter-api_key"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ipam_host_gather_module__parameter-api_key:

      .. rst-class:: ansible-option-title

      **api_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-api_key" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configures the API token for authentication against Infoblox BloxOne platform.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-fields"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ipam_host_gather_module__parameter-fields:

      .. rst-class:: ansible-option-title

      **fields**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-fields" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      List of fields to be available from the gather results.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-filters"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ipam_host_gather_module__parameter-filters:

      .. rst-class:: ansible-option-title

      **filters**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-filters" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Filters the result based on the key, value provided .


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-host"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ipam_host_gather_module__parameter-host:

      .. rst-class:: ansible-option-title

      **host**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-host" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configures the Infoblox BloxOne host URL.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-state"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ipam_host_gather_module__parameter-state:

      .. rst-class:: ansible-option-title

      **state**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-state" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configures the state of the object on BloxOne DDI. When this value is set to :literal:`get`\ , the object details are fetched (if present) from the platform, when this value is set to :literal:`present`\ , the object is configured on the platform and when this value is set to :literal:`absent` the value is removed (if necessary) from the platform.


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`"present"` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`"absent"`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-tfilters"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ipam_host_gather_module__parameter-tfilters:

      .. rst-class:: ansible-option-title

      **tfilters**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-tfilters" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Filters the result based on the Tag key, value provided .


      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    - name: Gather Host
      b1_ipam_host_gather:
        host: "{{ host }}"
        api_key: "{{ api }}"
        state: gather



.. Facts


.. Return values


..  Status (Presently only deprecated)

Status
------

.. Deprecated note

- This module will be removed in version 3.0.0.
  *[deprecated]*
- For more information see `DEPRECATED`_.


.. Authors

Authors
~~~~~~~

- Akhilesh Kabade (@akhilesh-kabade-infoblox)



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
