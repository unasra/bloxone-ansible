.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.15.0

.. Anchors

.. _ansible_collections.infoblox.bloxone.ipam_next_available_address_block_info_module:

.. Anchors: short name for ansible.builtin

.. Title

infoblox.bloxone.ipam_next_available_address_block_info module -- Manage NextAvailableAddressBlock
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `infoblox.bloxone collection <https://galaxy.ansible.com/ui/repo/published/infoblox/bloxone/>`_ (version 2.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install infoblox.bloxone`.

    To use it in a playbook, specify: :code:`infoblox.bloxone.ipam_next_available_address_block_info`.

.. version_added

.. rst-class:: ansible-version-added

New in infoblox.bloxone 2.0.0

.. contents::
   :local:
   :depth: 1

.. Deprecated


Synopsis
--------

.. Description

- Manage NextAvailableAddressBlock


.. Aliases


.. Requirements






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
        <div class="ansibleOptionAnchor" id="parameter-bloxone_api_key"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_next_available_address_block_info_module__parameter-api_key:
      .. _ansible_collections.infoblox.bloxone.ipam_next_available_address_block_info_module__parameter-bloxone_api_key:

      .. rst-class:: ansible-option-title

      **api_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-api_key" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-aliases:`aliases: bloxone_api_key`

        :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      The API token for authentication against Infoblox BloxOne API. If not set, the environment variable :ansenvvar:`BLOXONE\_API\_KEY` will be used.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-cidr"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_next_available_address_block_info_module__parameter-cidr:

      .. rst-class:: ansible-option-title

      **cidr**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-cidr" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      The CIDR value of the object


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-count"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_next_available_address_block_info_module__parameter-count:

      .. rst-class:: ansible-option-title

      **count**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-count" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Number of objects to generate. Default 1 if not set


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-csp_url"></div>
        <div class="ansibleOptionAnchor" id="parameter-bloxone_csp_url"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_next_available_address_block_info_module__parameter-bloxone_csp_url:
      .. _ansible_collections.infoblox.bloxone.ipam_next_available_address_block_info_module__parameter-csp_url:

      .. rst-class:: ansible-option-title

      **csp_url**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-csp_url" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-aliases:`aliases: bloxone_csp_url`

        :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      The Infoblox Cloud Services Portal (CSP) URL. If not set, the environment variable :ansenvvar:`BLOXONE\_CSP\_URL` will be used.


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"https://csp.infoblox.com"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-id"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_next_available_address_block_info_module__parameter-id:

      .. rst-class:: ansible-option-title

      **id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-id" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string` / :ansible-option-required:`required`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      ID of the object


      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


.. Examples

Examples
--------

.. code-block:: yaml+jinja

    - name: "Create an Address Block"
      infoblox.bloxone.ipam_address_block:
        address: "10.0.0.0/16"
        space: "{{ ip_space.id }}"
        state: "present"

    - name: Get Next Available Address Block Information by ID
      infoblox.bloxone.ipam_next_available_address_block_info:
          id: "{{ address_block.id }}"
          cidr: 20

    - name: Get Next Available Address Block Information by ID and Count
      infoblox.bloxone.ipam_next_available_address_block_info:
        id: "{{ address_block.id }}"
        cidr: 24
        count: 5



.. Facts


.. Return values

Return Values
-------------
Common return values are documented :ref:`here <common_return_values>`, the following are the fields unique to this module:

.. tabularcolumns:: \X{1}{3}\X{2}{3}

.. list-table::
  :width: 100%
  :widths: auto
  :header-rows: 1
  :class: longtable ansible-option-table

  * - Key
    - Description

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-id"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_next_available_address_block_info_module__return-id:

      .. rst-class:: ansible-option-title

      **id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-id" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      ID of the AddressBlock object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_next_available_address_block_info_module__return-objects:

      .. rst-class:: ansible-option-title

      **objects**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      List of next available address block's addresses.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



..  Status (Presently only deprecated)


.. Authors

Authors
~~~~~~~

- Infoblox Inc. (@infobloxopen)



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
