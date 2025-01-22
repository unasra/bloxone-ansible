.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.15.0

.. Anchors

.. _ansible_collections.infoblox.bloxone.b1_ptr_record_module:

.. Anchors: short name for ansible.builtin

.. Title

infoblox.bloxone.b1_ptr_record module -- Configure DNS Authoritative Zone on Infoblox BloxOne DDI
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `infoblox.bloxone collection <https://galaxy.ansible.com/ui/repo/published/infoblox/bloxone/>`_ (version 2.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install infoblox.bloxone`.
    You need further requirements to be able to use this module,
    see :ref:`Requirements <ansible_collections.infoblox.bloxone.b1_ptr_record_module_requirements>` for details.

    To use it in a playbook, specify: :code:`infoblox.bloxone.b1_ptr_record`.

.. version_added

.. rst-class:: ansible-version-added

New in infoblox.bloxone 1.0.1

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- Get, Create, Update and Delete DNS Authoritative Zone on Infoblox BloxOne DDI. This module manages the DNS Authoritative Zone object using BloxOne REST APIs.


.. Aliases


.. Requirements

.. _ansible_collections.infoblox.bloxone.b1_ptr_record_module_requirements:

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

      .. _ansible_collections.infoblox.bloxone.b1_ptr_record_module__parameter-api_key:

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

      Configures the API token for authentication against Infoblox BloxOne patform.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-comment"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ptr_record_module__parameter-comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-comment" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configures the comment/description for the DNS Authoritative Zone object to add or update from the system.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-external_primaries"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ptr_record_module__parameter-external_primaries:

      .. rst-class:: ansible-option-title

      **external_primaries**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-external_primaries" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configures the external primary DNS server associated with the DNS Authoritative Zone object to add or update from the system.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-fqdn"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ptr_record_module__parameter-fqdn:

      .. rst-class:: ansible-option-title

      **fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-fqdn" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configures the fqdn of the DNS Authoritative Zone to fetch, add, update or remove from the system. The fqdn of the DNS Authoritative Zone can be in forward or reverse domain name.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-host"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ptr_record_module__parameter-host:

      .. rst-class:: ansible-option-title

      **host**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-host" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configures the Infoblox BloxOne host URL.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-internal_secondaries"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ptr_record_module__parameter-internal_secondaries:

      .. rst-class:: ansible-option-title

      **internal_secondaries**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-internal_secondaries" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configures the DNS Server configured on Bloxone for the DNS Authoritative Zone to fetch, add, update or remove from the system.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-primary_type"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ptr_record_module__parameter-primary_type:

      .. rst-class:: ansible-option-title

      **primary_type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-primary_type" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configures the type of the DNS Authoritative Zone object to fetch, add, update or remove from the system. Default is set to 'cloud'.


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry:`"cloud"`
      - :ansible-option-choices-entry:`"external"`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-state"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ptr_record_module__parameter-state:

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

      Configures the state of the DNS Authoritative Zone object on BloxOne DDI. When this value is set to :literal:`get`\ , the object details are fetched (if present) from the platform, when this value is set to :literal:`present`\ , the object is configured on the platform and when this value is set to :literal:`absent` the value is removed (if necessary) from the platform.


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`"present"` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`"absent"`
      - :ansible-option-choices-entry:`"get"`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-tags"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ptr_record_module__parameter-tags:

      .. rst-class:: ansible-option-title

      **tags**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-tags" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configures the tags associated with the DNS Authoritative Zone object to add or update from the system.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-view"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ptr_record_module__parameter-view:

      .. rst-class:: ansible-option-title

      **view**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-view" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configures the name of DNS View containing the DNS Authoritative Zone to fetch, add, update or remove from the system.


      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    - name: GET all PTR Record
      b1_ptr_record:
        api_key: "{{ api_key }}"
        host: "{{ host }}"
        state: get

    - name: GET all PTR record of a zone
      b1_ptr_record:
        api_key: "{{ api_key }}"
        host: "{{ host }}"
        zone: "{{ Zone_name }}"
        state: get

    - name: GET Specific PTR record
      b1_ptr_record:
        api_key: "{{ api_key }}"
        host: "{{ host }}"
        zone: "{{ Zone_name }}"
        name: "{{ domain name of PTR record }"
        state: get

    - name: Create PTR record
      b1_ptr_record:
        api_key: "{{ api_key }}"
        host: "{{ host }}"
        zone: "{{ Zone_name }}"
        address: "{{ address of PTR record }}"
        name: "{{ domain name of PTR record }"
        state: present

    - name: UPDATE PTR record
      b1_ptr_record:
        api_key: "{{ api_key }}"
        host: "{{ host }}"
        zone: "{{ Zone_name }}"
        address:  "{{ address of PTR record }}"
        name: '{"new_name": "New domain name of PTR record", "old_name": "Old Domain of PTR record"}'
        state: present

    - name: Delete PTR record
      b1_ptr_record:
        api_key: "{{ api_key }}"
        host: "{{ host }}"
        zone: "{{ Zone_name }}"
        name: "{{ domain name of PTR record }"
        address:  "{{ address of PTR record }}"
        state: absent



.. Facts


.. Return values


..  Status (Presently only deprecated)


.. Authors

Authors
~~~~~~~

- Vedant Sethia (@vedantsethia)



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
