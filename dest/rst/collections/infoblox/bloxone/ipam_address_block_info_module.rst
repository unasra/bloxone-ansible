.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.15.0

.. Anchors

.. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module:

.. Anchors: short name for ansible.builtin

.. Title

infoblox.bloxone.ipam_address_block_info module -- Manage AddressBlock
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `infoblox.bloxone collection <https://galaxy.ansible.com/ui/repo/published/infoblox/bloxone/>`_ (version 2.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install infoblox.bloxone`.

    To use it in a playbook, specify: :code:`infoblox.bloxone.ipam_address_block_info`.

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

- Manage AddressBlock


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

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__parameter-api_key:
      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__parameter-bloxone_api_key:

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
        <div class="ansibleOptionAnchor" id="parameter-csp_url"></div>
        <div class="ansibleOptionAnchor" id="parameter-bloxone_csp_url"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__parameter-bloxone_csp_url:
      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__parameter-csp_url:

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
        <div class="ansibleOptionAnchor" id="parameter-filter_query"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__parameter-filter_query:

      .. rst-class:: ansible-option-title

      **filter_query**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-filter_query" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Filter query to filter objects


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-filters"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__parameter-filters:

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

      Filter dict to filter objects


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-id"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__parameter-id:

      .. rst-class:: ansible-option-title

      **id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-id" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      ID of the object


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-inherit"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__parameter-inherit:

      .. rst-class:: ansible-option-title

      **inherit**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-inherit" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Return inheritance information


      .. rst-class:: ansible-option-line

      :ansible-option-choices:`Choices:`

      - :ansible-option-choices-entry-default:`"full"` :ansible-option-choices-default-mark:`← (default)`
      - :ansible-option-choices-entry:`"partial"`
      - :ansible-option-choices-entry:`"none"`


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-tag_filter_query"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__parameter-tag_filter_query:

      .. rst-class:: ansible-option-title

      **tag_filter_query**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-tag_filter_query" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Filter query to filter objects by tags


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-tag_filters"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__parameter-tag_filters:

      .. rst-class:: ansible-option-title

      **tag_filters**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-tag_filters" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Filter dict to filter objects by tags


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
        tags:
          location: "site-1"
        state: "present"

    - name: Get Address Block information by ID
      infoblox.bloxone.ipam_address_block_info:
        id: "{{ address_block.id }}"

    - name: Get Address Block information by filters
      infoblox.bloxone.ipam_address_block_info:
        filters:
          address: "10.0.0.0/16"
          space: "{{ ip_space.id }}"

    - name: Get Address Block information by filter query
      infoblox.bloxone.ipam_address_block_info:
        filters_query: "address=='10.0.0.0/16' and space=='{{ ip_space.id }}'"

    - name: Get Address Block information by tag filters
      infoblox.bloxone.ipam_address_block_info:
        tag_filters:
          location: "site-1"



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

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-id:

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

      ID of the AddressBlock object


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects"></div>

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects:

      .. rst-class:: ansible-option-title

      **objects**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      AddressBlock object


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/address"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The address field in form "a.b.c.d/n" where the "/n" may be omitted. In this case, the CIDR value must be defined in the :emphasis:`cidr` field. When reading, the :emphasis:`address` field is always in the form "a.b.c.d".


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/asm_config"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/asm_config:

      .. rst-class:: ansible-option-title

      **asm_config**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/asm_config" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The Automated Scope Management configuration for the address block.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/asm_config/asm_threshold"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/asm_config/asm_threshold:

      .. rst-class:: ansible-option-title

      **asm_threshold**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/asm_config/asm_threshold" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      ASM shows the number of addresses forecast to be used :emphasis:`forecast\_period` days in the future, if it is greater than :emphasis:`asm\_threshold` percent \* :emphasis:`dhcp\_total` (see :emphasis:`dhcp\_utilization`\ ) then the subnet is flagged.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/asm_config/enable"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/asm_config/enable:

      .. rst-class:: ansible-option-title

      **enable**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/asm_config/enable" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Indicates if Automated Scope Management is enabled.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/asm_config/enable_notification"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/asm_config/enable_notification:

      .. rst-class:: ansible-option-title

      **enable_notification**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/asm_config/enable_notification" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Indicates if ASM should send notifications to the user.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/asm_config/forecast_period"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/asm_config/forecast_period:

      .. rst-class:: ansible-option-title

      **forecast_period**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/asm_config/forecast_period" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The forecast period in days.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/asm_config/growth_factor"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/asm_config/growth_factor:

      .. rst-class:: ansible-option-title

      **growth_factor**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/asm_config/growth_factor" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Indicates the growth in the number or percentage of IP addresses.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/asm_config/growth_type"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/asm_config/growth_type:

      .. rst-class:: ansible-option-title

      **growth_type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/asm_config/growth_type" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The type of factor to use: :emphasis:`percent` or :emphasis:`count`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/asm_config/history"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/asm_config/history:

      .. rst-class:: ansible-option-title

      **history**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/asm_config/history" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The minimum amount of history needed before ASM can run on this subnet.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/asm_config/min_total"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/asm_config/min_total:

      .. rst-class:: ansible-option-title

      **min_total**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/asm_config/min_total" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The minimum size of range needed for ASM to run on this subnet.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/asm_config/min_unused"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/asm_config/min_unused:

      .. rst-class:: ansible-option-title

      **min_unused**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/asm_config/min_unused" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The minimum percentage of addresses that must be available outside of the DHCP ranges and fixed addresses when making a suggested change..


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/asm_config/reenable_date"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/asm_config/reenable_date:

      .. rst-class:: ansible-option-title

      **reenable_date**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/asm_config/reenable_date" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The date at which notifications will be re-enabled automatically.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/asm_scope_flag"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/asm_scope_flag:

      .. rst-class:: ansible-option-title

      **asm_scope_flag**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/asm_scope_flag" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Incremented by 1 if the IP address usage limits for automated scope management are exceeded for any subnets in the address block.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/cidr"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/cidr:

      .. rst-class:: ansible-option-title

      **cidr**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/cidr" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The CIDR of the address block. This is required, if :emphasis:`address` does not specify it in its input.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/comment"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The description for the address block. May contain 0 to 1024 characters. Can include UTF-8.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/created_at"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/created_at:

      .. rst-class:: ansible-option-title

      **created_at**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/created_at" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Time when the object has been created.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ddns_client_update"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/ddns_client_update:

      .. rst-class:: ansible-option-title

      **ddns_client_update**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ddns_client_update" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Controls who does the DDNS updates.

      Valid values are:

      \* :emphasis:`client`\ : DHCP server updates DNS if requested by client.

      \* :emphasis:`server`\ : DHCP server always updates DNS, overriding an update request from the client, unless the client requests no updates.

      \* :emphasis:`ignore`\ : DHCP server always updates DNS, even if the client says not to.

      \* :emphasis:`over\_client\_update`\ : Same as :emphasis:`server`. DHCP server always updates DNS, overriding an update request from the client, unless the client requests no updates.

      \* :emphasis:`over\_no\_update`\ : DHCP server updates DNS even if the client requests that no updates be done. If the client requests to do the update, DHCP server allows it.

      Defaults to :emphasis:`client`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ddns_conflict_resolution_mode"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/ddns_conflict_resolution_mode:

      .. rst-class:: ansible-option-title

      **ddns_conflict_resolution_mode**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ddns_conflict_resolution_mode" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The mode used for resolving conflicts while performing DDNS updates.

      Valid values are:

      \* :emphasis:`check\_with\_dhcid`\ : It includes adding a DHCID record and checking that record via conflict detection as per RFC 4703.

      \* :emphasis:`no\_check\_with\_dhcid`\ : This will ignore conflict detection but add a DHCID record when creating/updating an entry.

      \* :emphasis:`check\_exists\_with\_dhcid`\ : This will check if there is an existing DHCID record but does not verify the value of the record matches the update. This will also update the DHCID record for the entry.

      \* :emphasis:`no\_check\_without\_dhcid`\ : This ignores conflict detection and will not add a DHCID record when creating/updating a DDNS entry.

      Defaults to :emphasis:`check\_with\_dhcid`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ddns_domain"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/ddns_domain:

      .. rst-class:: ansible-option-title

      **ddns_domain**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ddns_domain" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The domain suffix for DDNS updates. FQDN, may be empty.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ddns_generate_name"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/ddns_generate_name:

      .. rst-class:: ansible-option-title

      **ddns_generate_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ddns_generate_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Indicates if DDNS needs to generate a hostname when not supplied by the client.

      Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ddns_generated_prefix"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/ddns_generated_prefix:

      .. rst-class:: ansible-option-title

      **ddns_generated_prefix**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ddns_generated_prefix" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The prefix used in the generation of an FQDN.

      When generating a name, DHCP server will construct the name in the format: [ddns-generated-prefix]-[address-text].[ddns-qualifying-suffix]. where address-text is simply the lease IP address converted to a hyphenated string.

      Defaults to "myhost".


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ddns_send_updates"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/ddns_send_updates:

      .. rst-class:: ansible-option-title

      **ddns_send_updates**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ddns_send_updates" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Determines if DDNS updates are enabled at the address block level. Defaults to :emphasis:`true`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ddns_ttl_percent"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/ddns_ttl_percent:

      .. rst-class:: ansible-option-title

      **ddns_ttl_percent**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ddns_ttl_percent" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`float`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      DDNS TTL value - to be calculated as a simple percentage of the lease's lifetime, using the parameter's value as the percentage. It is specified as a percentage (e.g. 25, 75). Defaults to unspecified.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ddns_update_on_renew"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/ddns_update_on_renew:

      .. rst-class:: ansible-option-title

      **ddns_update_on_renew**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ddns_update_on_renew" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Instructs the DHCP server to always update the DNS information when a lease is renewed even if its DNS information has not changed.

      Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ddns_use_conflict_resolution"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/ddns_use_conflict_resolution:

      .. rst-class:: ansible-option-title

      **ddns_use_conflict_resolution**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ddns_use_conflict_resolution" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      When true, DHCP server will apply conflict resolution, as described in RFC 4703, when attempting to fulfill the update request.

      When false, DHCP server will simply attempt to update the DNS entries per the request, regardless of whether or not they conflict with existing entries owned by other DHCP4 clients.

      Defaults to :emphasis:`true`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config:

      .. rst-class:: ansible-option-title

      **dhcp_config**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The shared DHCP configuration that controls how leases are issued for the address block.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/abandoned_reclaim_time"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/abandoned_reclaim_time:

      .. rst-class:: ansible-option-title

      **abandoned_reclaim_time**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/abandoned_reclaim_time" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The abandoned reclaim time in seconds for IPV4 clients.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/abandoned_reclaim_time_v6"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/abandoned_reclaim_time_v6:

      .. rst-class:: ansible-option-title

      **abandoned_reclaim_time_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/abandoned_reclaim_time_v6" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The abandoned reclaim time in seconds for IPV6 clients.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/allow_unknown"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/allow_unknown:

      .. rst-class:: ansible-option-title

      **allow_unknown**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/allow_unknown" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Disable to allow leases only for known IPv4 clients, those for which a fixed address is configured.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/allow_unknown_v6"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/allow_unknown_v6:

      .. rst-class:: ansible-option-title

      **allow_unknown_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/allow_unknown_v6" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Disable to allow leases only for known IPV6 clients, those for which a fixed address is configured.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/echo_client_id"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/echo_client_id:

      .. rst-class:: ansible-option-title

      **echo_client_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/echo_client_id" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Enable/disable to include/exclude the client id when responding to discover or request.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/filters"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/filters:

      .. rst-class:: ansible-option-title

      **filters**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/filters" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/filters_v6"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/filters_v6:

      .. rst-class:: ansible-option-title

      **filters_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/filters_v6" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/ignore_client_uid"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/ignore_client_uid:

      .. rst-class:: ansible-option-title

      **ignore_client_uid**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/ignore_client_uid" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Enable to ignore the client UID when issuing a DHCP lease. Use this option to prevent assigning two IP addresses for a client which does not have a UID during one phase of PXE boot but acquires one for the other phase.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/ignore_list"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/ignore_list:

      .. rst-class:: ansible-option-title

      **ignore_list**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/ignore_list" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The list of clients to ignore requests from.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/ignore_list/type"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/ignore_list/type:

      .. rst-class:: ansible-option-title

      **type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/ignore_list/type" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of ignore matching: client to ignore by client identifier (client hex or client text) or hardware to ignore by hardware identifier (MAC address). It can have one of the following values:

      \* :emphasis:`client\_hex`\ ,

      \* :emphasis:`client\_text`\ ,

      \* :emphasis:`hardware`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/ignore_list/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/ignore_list/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/ignore_list/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Value to match.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/lease_time"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/lease_time:

      .. rst-class:: ansible-option-title

      **lease_time**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/lease_time" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The lease duration in seconds.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_config/lease_time_v6"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_config/lease_time_v6:

      .. rst-class:: ansible-option-title

      **lease_time_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_config/lease_time_v6" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The lease duration in seconds for IPV6 clients.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_options"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_options:

      .. rst-class:: ansible-option-title

      **dhcp_options**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_options" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The list of DHCP options for the address block. May be either a specific option or a group of options.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_options/group"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_options/group:

      .. rst-class:: ansible-option-title

      **group**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_options/group" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_options/option_code"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_options/option_code:

      .. rst-class:: ansible-option-title

      **option_code**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_options/option_code" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_options/option_value"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_options/option_value:

      .. rst-class:: ansible-option-title

      **option_value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_options/option_value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The option value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_options/type"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_options/type:

      .. rst-class:: ansible-option-title

      **type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_options/type" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The type of item.

      Valid values are:

      \* :emphasis:`group`

      \* :emphasis:`option`


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_utilization"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_utilization:

      .. rst-class:: ansible-option-title

      **dhcp_utilization**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_utilization" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The utilization of IP addresses within the DHCP ranges of the address block.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_utilization/dhcp_free"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_utilization/dhcp_free:

      .. rst-class:: ansible-option-title

      **dhcp_free**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_utilization/dhcp_free" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The total free IP addresses in the DHCP ranges in the scope of this object. It can be computed as :emphasis:`dhcp\_total` - :emphasis:`dhcp\_used`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_utilization/dhcp_total"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_utilization/dhcp_total:

      .. rst-class:: ansible-option-title

      **dhcp_total**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_utilization/dhcp_total" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The total IP addresses available in the DHCP ranges in the scope of this object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_utilization/dhcp_used"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_utilization/dhcp_used:

      .. rst-class:: ansible-option-title

      **dhcp_used**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_utilization/dhcp_used" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The total IP addresses marked as used in the DHCP ranges in the scope of this object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dhcp_utilization/dhcp_utilization"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/dhcp_utilization/dhcp_utilization:

      .. rst-class:: ansible-option-title

      **dhcp_utilization**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dhcp_utilization/dhcp_utilization" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The percentage of used IP addresses relative to the total IP addresses available in the DHCP ranges in the scope of this object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/discovery_attrs"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/discovery_attrs:

      .. rst-class:: ansible-option-title

      **discovery_attrs**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/discovery_attrs" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The discovery attributes for this address block in JSON format.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/discovery_metadata"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/discovery_metadata:

      .. rst-class:: ansible-option-title

      **discovery_metadata**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/discovery_metadata" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The discovery metadata for this address block in JSON format.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/header_option_filename"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/header_option_filename:

      .. rst-class:: ansible-option-title

      **header_option_filename**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/header_option_filename" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The configuration for header option filename field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/header_option_server_address"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/header_option_server_address:

      .. rst-class:: ansible-option-title

      **header_option_server_address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/header_option_server_address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The configuration for header option server address field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/header_option_server_name"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/header_option_server_name:

      .. rst-class:: ansible-option-title

      **header_option_server_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/header_option_server_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The configuration for header option server name field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/hostname_rewrite_char"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/hostname_rewrite_char:

      .. rst-class:: ansible-option-title

      **hostname_rewrite_char**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/hostname_rewrite_char" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The character to replace non-matching characters with, when hostname rewrite is enabled.

      Any single ASCII character or no character if the invalid characters should be removed without replacement.

      Defaults to "-".


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/hostname_rewrite_enabled"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/hostname_rewrite_enabled:

      .. rst-class:: ansible-option-title

      **hostname_rewrite_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/hostname_rewrite_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Indicates if client supplied hostnames will be rewritten prior to DDNS update by replacing every character that does not match :emphasis:`hostname\_rewrite\_regex` by :emphasis:`hostname\_rewrite\_char`.

      Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/hostname_rewrite_regex"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/hostname_rewrite_regex:

      .. rst-class:: ansible-option-title

      **hostname_rewrite_regex**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/hostname_rewrite_regex" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The regex bracket expression to match valid characters.

      Must begin with "[" and end with "]" and be a compilable POSIX regex.

      Defaults to "[^a-zA-Z0-9\_.]".


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/id"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/id:

      .. rst-class:: ansible-option-title

      **id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/id" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_parent"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_parent:

      .. rst-class:: ansible-option-title

      **inheritance_parent**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_parent" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources:

      .. rst-class:: ansible-option-title

      **inheritance_sources**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The DHCP inheritance configuration for the address block.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config:

      .. rst-class:: ansible-option-title

      **asm_config**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`asm\_config` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_enable_block"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_enable_block:

      .. rst-class:: ansible-option-title

      **asm_enable_block**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_enable_block" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The block of ASM fields: :emphasis:`enable`\ , :emphasis:`enable\_notification`\ , :emphasis:`reenable\_date`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_enable_block/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_enable_block/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_enable_block/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_enable_block/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_enable_block/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_enable_block/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_enable_block/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_enable_block/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_enable_block/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_enable_block/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_enable_block/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_enable_block/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_enable_block/value/enable"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_enable_block/value/enable:

      .. rst-class:: ansible-option-title

      **enable**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_enable_block/value/enable" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Indicates whether Automated Scope Management is enabled or not.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_enable_block/value/enable_notification"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_enable_block/value/enable_notification:

      .. rst-class:: ansible-option-title

      **enable_notification**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_enable_block/value/enable_notification" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Indicates whether sending notifications to the users is enabled or not.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_enable_block/value/reenable_date"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_enable_block/value/reenable_date:

      .. rst-class:: ansible-option-title

      **reenable_date**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_enable_block/value/reenable_date" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The date at which notifications will be re-enabled automatically.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_growth_block"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_growth_block:

      .. rst-class:: ansible-option-title

      **asm_growth_block**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_growth_block" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The block of ASM fields: :emphasis:`growth\_factor`\ , :emphasis:`growth\_type`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_growth_block/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_growth_block/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_growth_block/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_growth_block/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_growth_block/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_growth_block/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_growth_block/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_growth_block/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_growth_block/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_growth_block/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_growth_block/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_growth_block/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_growth_block/value/growth_factor"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_growth_block/value/growth_factor:

      .. rst-class:: ansible-option-title

      **growth_factor**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_growth_block/value/growth_factor" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Either the number or percentage of addresses to grow by.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_growth_block/value/growth_type"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_growth_block/value/growth_type:

      .. rst-class:: ansible-option-title

      **growth_type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_growth_block/value/growth_type" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The type of factor to use: :emphasis:`percent` or :emphasis:`count`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_threshold"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_threshold:

      .. rst-class:: ansible-option-title

      **asm_threshold**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_threshold" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      ASM shows the number of addresses forecast to be used :emphasis:`forecast\_period` days in the future, if it is greater than :emphasis:`asm\_threshold\_percent` \* :emphasis:`dhcp\_total` (see :emphasis:`dhcp\_utilization`\ ) then the subnet is flagged.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_threshold/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_threshold/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_threshold/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_threshold/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_threshold/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_threshold/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_threshold/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_threshold/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_threshold/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/asm_threshold/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/asm_threshold/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/asm_threshold/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/forecast_period"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/forecast_period:

      .. rst-class:: ansible-option-title

      **forecast_period**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/forecast_period" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The forecast period in days.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/forecast_period/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/forecast_period/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/forecast_period/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/forecast_period/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/forecast_period/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/forecast_period/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/forecast_period/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/forecast_period/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/forecast_period/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/forecast_period/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/forecast_period/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/forecast_period/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/history"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/history:

      .. rst-class:: ansible-option-title

      **history**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/history" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The minimum amount of history needed before ASM can run on this subnet.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/history/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/history/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/history/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/history/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/history/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/history/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/history/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/history/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/history/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/history/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/history/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/history/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/min_total"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/min_total:

      .. rst-class:: ansible-option-title

      **min_total**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/min_total" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The minimum size of range needed for ASM to run on this subnet.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/min_total/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/min_total/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/min_total/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/min_total/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/min_total/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/min_total/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/min_total/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/min_total/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/min_total/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/min_total/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/min_total/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/min_total/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/min_unused"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/min_unused:

      .. rst-class:: ansible-option-title

      **min_unused**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/min_unused" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The minimum percentage of addresses that must be available outside of the DHCP ranges and fixed addresses when making a suggested change.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/min_unused/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/min_unused/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/min_unused/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/min_unused/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/min_unused/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/min_unused/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/min_unused/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/min_unused/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/min_unused/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/asm_config/min_unused/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/asm_config/min_unused/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/asm_config/min_unused/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_client_update"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_client_update:

      .. rst-class:: ansible-option-title

      **ddns_client_update**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_client_update" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`ddns\_client\_update` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_client_update/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_client_update/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_client_update/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_client_update/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_client_update/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_client_update/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_client_update/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_client_update/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_client_update/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_client_update/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_client_update/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_client_update/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_conflict_resolution_mode"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_conflict_resolution_mode:

      .. rst-class:: ansible-option-title

      **ddns_conflict_resolution_mode**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_conflict_resolution_mode" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`ddns\_conflict\_resolution\_mode` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_conflict_resolution_mode/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_conflict_resolution_mode/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_conflict_resolution_mode/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_conflict_resolution_mode/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_conflict_resolution_mode/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_conflict_resolution_mode/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_conflict_resolution_mode/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_conflict_resolution_mode/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_conflict_resolution_mode/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_conflict_resolution_mode/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_conflict_resolution_mode/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_conflict_resolution_mode/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_enabled"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_enabled:

      .. rst-class:: ansible-option-title

      **ddns_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`ddns\_enabled` field. Only action allowed is 'inherit'.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_enabled/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_enabled/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_enabled/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_enabled/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_enabled/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_enabled/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_enabled/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_enabled/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_enabled/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_enabled/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_enabled/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_enabled/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_hostname_block"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_hostname_block:

      .. rst-class:: ansible-option-title

      **ddns_hostname_block**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_hostname_block" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`ddns\_generate\_name` and :emphasis:`ddns\_generated\_prefix` fields.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_hostname_block/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_hostname_block/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_hostname_block/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_hostname_block/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_hostname_block/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_hostname_block/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_hostname_block/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_hostname_block/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_hostname_block/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_hostname_block/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_hostname_block/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_hostname_block/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_hostname_block/value/ddns_generate_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_hostname_block/value/ddns_generate_name:

      .. rst-class:: ansible-option-title

      **ddns_generate_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_hostname_block/value/ddns_generate_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Indicates if DDNS should generate a hostname when not supplied by the client.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_hostname_block/value/ddns_generated_prefix"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_hostname_block/value/ddns_generated_prefix:

      .. rst-class:: ansible-option-title

      **ddns_generated_prefix**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_hostname_block/value/ddns_generated_prefix" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The prefix used in the generation of an FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_ttl_percent"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_ttl_percent:

      .. rst-class:: ansible-option-title

      **ddns_ttl_percent**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_ttl_percent" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`ddns\_ttl\_percent` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_ttl_percent/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_ttl_percent/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_ttl_percent/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_ttl_percent/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_ttl_percent/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_ttl_percent/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_ttl_percent/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_ttl_percent/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_ttl_percent/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_ttl_percent/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_ttl_percent/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_ttl_percent/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`float`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_update_block"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_update_block:

      .. rst-class:: ansible-option-title

      **ddns_update_block**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_update_block" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`ddns\_send\_updates` and :emphasis:`ddns\_domain` fields.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_update_block/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_update_block/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_update_block/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_update_block/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_update_block/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_update_block/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_update_block/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_update_block/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_update_block/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_update_block/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_update_block/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_update_block/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_update_block/value/ddns_domain"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_update_block/value/ddns_domain:

      .. rst-class:: ansible-option-title

      **ddns_domain**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_update_block/value/ddns_domain" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The domain name for DDNS.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_update_block/value/ddns_send_updates"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_update_block/value/ddns_send_updates:

      .. rst-class:: ansible-option-title

      **ddns_send_updates**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_update_block/value/ddns_send_updates" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Determines if DDNS updates are enabled at this level.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_update_on_renew"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_update_on_renew:

      .. rst-class:: ansible-option-title

      **ddns_update_on_renew**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_update_on_renew" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`ddns\_update\_on\_renew` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_update_on_renew/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_update_on_renew/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_update_on_renew/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_update_on_renew/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_update_on_renew/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_update_on_renew/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_update_on_renew/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_update_on_renew/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_update_on_renew/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_update_on_renew/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_update_on_renew/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_update_on_renew/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_use_conflict_resolution"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_use_conflict_resolution:

      .. rst-class:: ansible-option-title

      **ddns_use_conflict_resolution**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_use_conflict_resolution" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`ddns\_use\_conflict\_resolution` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_use_conflict_resolution/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_use_conflict_resolution/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_use_conflict_resolution/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_use_conflict_resolution/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_use_conflict_resolution/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_use_conflict_resolution/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_use_conflict_resolution/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_use_conflict_resolution/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_use_conflict_resolution/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ddns_use_conflict_resolution/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/ddns_use_conflict_resolution/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ddns_use_conflict_resolution/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config:

      .. rst-class:: ansible-option-title

      **dhcp_config**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`dhcp\_config` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time:

      .. rst-class:: ansible-option-title

      **abandoned_reclaim_time**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`abandoned\_reclaim\_time` field from :emphasis:`DHCPConfig` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6:

      .. rst-class:: ansible-option-title

      **abandoned_reclaim_time_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`abandoned\_reclaim\_time\_v6` field from :emphasis:`DHCPConfig` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/abandoned_reclaim_time_v6/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/allow_unknown"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/allow_unknown:

      .. rst-class:: ansible-option-title

      **allow_unknown**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/allow_unknown" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`allow\_unknown` field from :emphasis:`DHCPConfig` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/allow_unknown/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/allow_unknown/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/allow_unknown/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/allow_unknown/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/allow_unknown/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/allow_unknown/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/allow_unknown/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/allow_unknown/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/allow_unknown/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/allow_unknown/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/allow_unknown/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/allow_unknown/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/allow_unknown_v6"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/allow_unknown_v6:

      .. rst-class:: ansible-option-title

      **allow_unknown_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/allow_unknown_v6" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`allow\_unknown\_v6` field from :emphasis:`DHCPConfig` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/allow_unknown_v6/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/allow_unknown_v6/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/allow_unknown_v6/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/allow_unknown_v6/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/allow_unknown_v6/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/allow_unknown_v6/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/allow_unknown_v6/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/allow_unknown_v6/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/allow_unknown_v6/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/allow_unknown_v6/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/allow_unknown_v6/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/allow_unknown_v6/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/echo_client_id"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/echo_client_id:

      .. rst-class:: ansible-option-title

      **echo_client_id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/echo_client_id" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`echo\_client\_id` field from :emphasis:`DHCPConfig` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/echo_client_id/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/echo_client_id/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/echo_client_id/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/echo_client_id/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/echo_client_id/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/echo_client_id/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/echo_client_id/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/echo_client_id/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/echo_client_id/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/echo_client_id/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/echo_client_id/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/echo_client_id/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/filters"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/filters:

      .. rst-class:: ansible-option-title

      **filters**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/filters" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for filters field from :emphasis:`DHCPConfig` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/filters/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/filters/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/filters/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/filters/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/filters/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/filters/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/filters/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/filters/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/filters/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/filters/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/filters/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/filters/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/filters_v6"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/filters_v6:

      .. rst-class:: ansible-option-title

      **filters_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/filters_v6" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`filters\_v6` field from :emphasis:`DHCPConfig` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/filters_v6/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/filters_v6/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/filters_v6/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/filters_v6/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/filters_v6/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/filters_v6/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/filters_v6/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/filters_v6/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/filters_v6/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/filters_v6/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/filters_v6/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/filters_v6/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/ignore_client_uid"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/ignore_client_uid:

      .. rst-class:: ansible-option-title

      **ignore_client_uid**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/ignore_client_uid" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`ignore\_client\_uid` field from :emphasis:`DHCPConfig` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/ignore_client_uid/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/ignore_client_uid/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/ignore_client_uid/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/ignore_client_uid/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/ignore_client_uid/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/ignore_client_uid/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/ignore_client_uid/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/ignore_client_uid/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/ignore_client_uid/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/ignore_client_uid/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/ignore_client_uid/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/ignore_client_uid/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/ignore_list"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/ignore_list:

      .. rst-class:: ansible-option-title

      **ignore_list**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/ignore_list" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`ignore\_list` field from :emphasis:`DHCPConfig` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/ignore_list/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/ignore_list/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/ignore_list/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/ignore_list/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/ignore_list/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/ignore_list/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/ignore_list/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/ignore_list/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/ignore_list/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/ignore_list/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/ignore_list/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/ignore_list/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/ignore_list/value/type"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/ignore_list/value/type:

      .. rst-class:: ansible-option-title

      **type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/ignore_list/value/type" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of ignore matching: client to ignore by client identifier (client hex or client text) or hardware to ignore by hardware identifier (MAC address). It can have one of the following values:

      \* :emphasis:`client\_hex`\ ,

      \* :emphasis:`client\_text`\ ,

      \* :emphasis:`hardware`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/ignore_list/value/value"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/ignore_list/value/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/ignore_list/value/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Value to match.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/lease_time"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/lease_time:

      .. rst-class:: ansible-option-title

      **lease_time**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/lease_time" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`lease\_time` field from :emphasis:`DHCPConfig` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/lease_time/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/lease_time/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/lease_time/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/lease_time/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/lease_time/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/lease_time/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/lease_time/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/lease_time/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/lease_time/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/lease_time/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/lease_time/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/lease_time/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/lease_time_v6"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/lease_time_v6:

      .. rst-class:: ansible-option-title

      **lease_time_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/lease_time_v6" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`lease\_time\_v6` field from :emphasis:`DHCPConfig` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/lease_time_v6/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/lease_time_v6/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/lease_time_v6/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/lease_time_v6/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/lease_time_v6/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/lease_time_v6/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/lease_time_v6/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/lease_time_v6/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/lease_time_v6/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_config/lease_time_v6/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_config/lease_time_v6/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_config/lease_time_v6/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options:

      .. rst-class:: ansible-option-title

      **dhcp_options**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`dhcp\_options` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`block`\ : Don't use the inherited value.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited DHCP option values.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options/value/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options/value/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options/value/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`block`\ : Don't use the inherited value.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options/value/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options/value/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options/value/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options/value/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options/value/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options/value/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options/value/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options/value/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options/value/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value for the DHCP option.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options/value/value/option"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options/value/value/option:

      .. rst-class:: ansible-option-title

      **option**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options/value/value/option" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Option inherited from the ancestor.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options/value/value/option/group"></div>

      .. raw:: latex

        \hspace{0.12\textwidth}\begin{minipage}[t]{0.2\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options/value/value/option/group:

      .. rst-class:: ansible-option-title

      **group**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options/value/value/option/group" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options/value/value/option/option_code"></div>

      .. raw:: latex

        \hspace{0.12\textwidth}\begin{minipage}[t]{0.2\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options/value/value/option/option_code:

      .. rst-class:: ansible-option-title

      **option_code**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options/value/value/option/option_code" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options/value/value/option/option_value"></div>

      .. raw:: latex

        \hspace{0.12\textwidth}\begin{minipage}[t]{0.2\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options/value/value/option/option_value:

      .. rst-class:: ansible-option-title

      **option_value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options/value/value/option/option_value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The option value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options/value/value/option/type"></div>

      .. raw:: latex

        \hspace{0.12\textwidth}\begin{minipage}[t]{0.2\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options/value/value/option/type:

      .. rst-class:: ansible-option-title

      **type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options/value/value/option/type" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The type of item.

      Valid values are:

      \* :emphasis:`group`

      \* :emphasis:`option`


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dhcp_options/value/value/overriding_group"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/dhcp_options/value/value/overriding_group:

      .. rst-class:: ansible-option-title

      **overriding_group**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dhcp_options/value/value/overriding_group" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>





  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_filename"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_filename:

      .. rst-class:: ansible-option-title

      **header_option_filename**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_filename" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`header\_option\_filename` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_filename/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_filename/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_filename/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_filename/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_filename/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_filename/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_filename/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_filename/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_filename/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_filename/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_filename/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_filename/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_server_address"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_server_address:

      .. rst-class:: ansible-option-title

      **header_option_server_address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_server_address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`header\_option\_server\_address` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_server_address/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_server_address/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_server_address/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_server_address/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_server_address/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_server_address/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_server_address/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_server_address/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_server_address/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_server_address/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_server_address/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_server_address/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_server_name"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_server_name:

      .. rst-class:: ansible-option-title

      **header_option_server_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_server_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`header\_option\_server\_name` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_server_name/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_server_name/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_server_name/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting for a field.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_server_name/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_server_name/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_server_name/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_server_name/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_server_name/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_server_name/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/header_option_server_name/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/header_option_server_name/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/header_option_server_name/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/hostname_rewrite_block"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/hostname_rewrite_block:

      .. rst-class:: ansible-option-title

      **hostname_rewrite_block**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/hostname_rewrite_block" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`hostname\_rewrite\_enabled`\ , :emphasis:`hostname\_rewrite\_regex`\ , and :emphasis:`hostname\_rewrite\_char` fields.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/hostname_rewrite_block/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/hostname_rewrite_block/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/hostname_rewrite_block/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance setting.

      Valid values are:

      \* :emphasis:`inherit`\ : Use the inherited value.

      \* :emphasis:`override`\ : Use the value set in the object.

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/hostname_rewrite_block/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/hostname_rewrite_block/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/hostname_rewrite_block/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/hostname_rewrite_block/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/hostname_rewrite_block/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/hostname_rewrite_block/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/hostname_rewrite_block/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/hostname_rewrite_block/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/hostname_rewrite_block/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/hostname_rewrite_block/value/hostname_rewrite_char"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/hostname_rewrite_block/value/hostname_rewrite_char:

      .. rst-class:: ansible-option-title

      **hostname_rewrite_char**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/hostname_rewrite_block/value/hostname_rewrite_char" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`hostname\_rewrite\_char` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/hostname_rewrite_block/value/hostname_rewrite_enabled"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/hostname_rewrite_block/value/hostname_rewrite_enabled:

      .. rst-class:: ansible-option-title

      **hostname_rewrite_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/hostname_rewrite_block/value/hostname_rewrite_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`hostname\_rewrite\_enabled` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/hostname_rewrite_block/value/hostname_rewrite_regex"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/inheritance_sources/hostname_rewrite_block/value/hostname_rewrite_regex:

      .. rst-class:: ansible-option-title

      **hostname_rewrite_regex**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/hostname_rewrite_block/value/hostname_rewrite_regex" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The inheritance configuration for :emphasis:`hostname\_rewrite\_regex` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>





  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/name"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The name of the address block. May contain 1 to 256 characters. Can include UTF-8.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/parent"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/parent:

      .. rst-class:: ansible-option-title

      **parent**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/parent" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/protocol"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/protocol:

      .. rst-class:: ansible-option-title

      **protocol**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/protocol" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The type of protocol of address block (\ :emphasis:`ip4` or :emphasis:`ip6`\ ).


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/space"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/space:

      .. rst-class:: ansible-option-title

      **space**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/space" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The resource identifier.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/tags"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/tags:

      .. rst-class:: ansible-option-title

      **tags**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/tags" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The tags for the address block in JSON format.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/threshold"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/threshold:

      .. rst-class:: ansible-option-title

      **threshold**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/threshold" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The IP address utilization thresholds for the address block.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/threshold/enabled"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/threshold/enabled:

      .. rst-class:: ansible-option-title

      **enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/threshold/enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Indicates whether the utilization threshold for IP addresses is enabled or not.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/threshold/high"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/threshold/high:

      .. rst-class:: ansible-option-title

      **high**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/threshold/high" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The high threshold value for the percentage of used IP addresses relative to the total IP addresses available in the scope of the object. Thresholds are inclusive in the comparison test.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/threshold/low"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/threshold/low:

      .. rst-class:: ansible-option-title

      **low**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/threshold/low" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The low threshold value for the percentage of used IP addresses relative to the total IP addresses available in the scope of the object. Thresholds are inclusive in the comparison test.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/updated_at"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/updated_at:

      .. rst-class:: ansible-option-title

      **updated_at**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/updated_at" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Time when the object has been updated. Equals to :emphasis:`created\_at` if not updated after creation.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/usage"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/usage:

      .. rst-class:: ansible-option-title

      **usage**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/usage" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The usage is a combination of indicators, each tracking a specific associated use. Listed below are usage indicators with their meaning: usage indicator | description ---------------------- | -------------------------------- :emphasis:`IPAM` | AddressBlock is managed in BloxOne DDI. :emphasis:`DISCOVERED` | AddressBlock is discovered by some network discovery probe like Network Insight or NetMRI in NIOS.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization:

      .. rst-class:: ansible-option-title

      **utilization**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The IPV4 address utilization statistics for the address block.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization/abandon_utilization"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization/abandon_utilization:

      .. rst-class:: ansible-option-title

      **abandon_utilization**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization/abandon_utilization" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The percentage of abandoned IP addresses relative to the total IP addresses available in the scope of the object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization/abandoned"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization/abandoned:

      .. rst-class:: ansible-option-title

      **abandoned**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization/abandoned" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The number of IP addresses in the scope of the object which are in the abandoned state (issued by a DHCP server and then declined by the client).


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization/dynamic"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization/dynamic:

      .. rst-class:: ansible-option-title

      **dynamic**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization/dynamic" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The number of IP addresses handed out by DHCP in the scope of the object. This includes all leased addresses, fixed addresses that are defined but not currently leased and abandoned leases.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization/free"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization/free:

      .. rst-class:: ansible-option-title

      **free**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization/free" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The number of IP addresses available in the scope of the object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization/static"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization/static:

      .. rst-class:: ansible-option-title

      **static**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization/static" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The number of defined IP addresses such as reservations or DNS records. It can be computed as :emphasis:`static` = :emphasis:`used` - :emphasis:`dynamic`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization/total"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization/total:

      .. rst-class:: ansible-option-title

      **total**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization/total" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The total number of IP addresses available in the scope of the object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization/used"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization/used:

      .. rst-class:: ansible-option-title

      **used**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization/used" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The number of IP addresses used in the scope of the object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization/utilization"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization/utilization:

      .. rst-class:: ansible-option-title

      **utilization**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization/utilization" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The percentage of used IP addresses relative to the total IP addresses available in the scope of the object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization_v6"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization_v6:

      .. rst-class:: ansible-option-title

      **utilization_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization_v6" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The utilization of IPV6 addresses in the Address block.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization_v6/abandoned"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization_v6/abandoned:

      .. rst-class:: ansible-option-title

      **abandoned**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization_v6/abandoned" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The number of IP addresses in the scope of the object which are in the abandoned state (issued by a DHCP server and then declined by the client).


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization_v6/dynamic"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization_v6/dynamic:

      .. rst-class:: ansible-option-title

      **dynamic**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization_v6/dynamic" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The number of IP addresses handed out by DHCP in the scope of the object. This includes all leased addresses, fixed addresses that are defined but not currently leased and abandoned leases.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization_v6/static"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization_v6/static:

      .. rst-class:: ansible-option-title

      **static**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization_v6/static" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The number of defined IP addresses such as reservations or DNS records. It can be computed as \_static\_ = \_used\_ - \_dynamic\_.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization_v6/total"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization_v6/total:

      .. rst-class:: ansible-option-title

      **total**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization_v6/total" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The total number of IP addresses available in the scope of the object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/utilization_v6/used"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.ipam_address_block_info_module__return-objects/utilization_v6/used:

      .. rst-class:: ansible-option-title

      **used**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/utilization_v6/used" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The number of IP addresses used in the scope of the object.


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
