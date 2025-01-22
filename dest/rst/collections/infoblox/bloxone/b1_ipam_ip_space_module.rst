.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.15.0

.. Anchors

.. _ansible_collections.infoblox.bloxone.b1_ipam_ip_space_module:

.. Anchors: short name for ansible.builtin

.. Title

infoblox.bloxone.b1_ipam_ip_space module -- Configure IP space on Infoblox BloxOne DDI
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `infoblox.bloxone collection <https://galaxy.ansible.com/ui/repo/published/infoblox/bloxone/>`_ (version 2.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install infoblox.bloxone`.
    You need further requirements to be able to use this module,
    see :ref:`Requirements <ansible_collections.infoblox.bloxone.b1_ipam_ip_space_module_requirements>` for details.

    To use it in a playbook, specify: :code:`infoblox.bloxone.b1_ipam_ip_space`.

.. version_added

.. rst-class:: ansible-version-added

New in infoblox.bloxone 1.0.1

.. contents::
   :local:
   :depth: 1

.. Deprecated

DEPRECATED
----------
:Removed in: version 3.0.0
:Why: This module is deprecated and will be removed in version 3.0.0. Use :ref:`infoblox.bloxone.ipam\_ip\_space <ansible_collections.infoblox.bloxone.ipam_ip_space_module>` instead.
:Alternative: Use :ref:`infoblox.bloxone.ipam\_ip\_space <ansible_collections.infoblox.bloxone.ipam_ip_space_module>` instead.

Synopsis
--------

.. Description

- Create, Update and Delete IP spaces on Infoblox BloxOne DDI. This module manages the IPAM IP space object using BloxOne REST APIs.


.. Aliases


.. Requirements

.. _ansible_collections.infoblox.bloxone.b1_ipam_ip_space_module_requirements:

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

      .. _ansible_collections.infoblox.bloxone.b1_ipam_ip_space_module__parameter-api_key:

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

      .. _ansible_collections.infoblox.bloxone.b1_ipam_ip_space_module__parameter-comment:

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

      Configures the comment/description for the object to add or update from the system.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-host"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ipam_ip_space_module__parameter-host:

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
        <div class="ansibleOptionAnchor" id="parameter-name"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ipam_ip_space_module__parameter-name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-name" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Configures the name of object to fetch, add, update or remove from the system. User can also update the name as it is possible to pass a dict containing :emphasis:`new\_name`\ , :emphasis:`old\_name`.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-state"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ipam_ip_space_module__parameter-state:

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
        <div class="ansibleOptionAnchor" id="parameter-tags"></div>

      .. _ansible_collections.infoblox.bloxone.b1_ipam_ip_space_module__parameter-tags:

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

      Configures the tags associated with the object to add or update from the system.


      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    - name: Create IP space
      b1_ipam_ip_space:
        name: "Test-Ansible-Space"
        tags:
          - "Org": "Infoblox"
          - "Dept": "Engineering"
        comment: "This is a test IPSpace to validate Infoblox Ansible Collection"
        host: "{{ host_server }}"
        api_key: "{{ api }}"
        state: present

    - name: Update the IPSpace
      b1_ipam_ip_space:
        name: "Test-Ansible-Space"
        tags:
          - "Status": "Working"
          - "GeoLoc": "India"
        host: "{{ host_server }}"
        api_key: "{{ api }}"
        state: present

    - name: Delete IP space
      b1_ipam_ip_space:
        name: "Test-Ansible-Space"
        host: "{{ host_server }}"
        api_key: "{{ api }}"
        state: absent



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

- Amit Mishra (@amishra), Sriram Kannan(@kannans)



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
