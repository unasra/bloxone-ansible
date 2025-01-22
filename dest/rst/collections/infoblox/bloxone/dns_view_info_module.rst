.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.15.0

.. Anchors

.. _ansible_collections.infoblox.bloxone.dns_view_info_module:

.. Anchors: short name for ansible.builtin

.. Title

infoblox.bloxone.dns_view_info module -- Manage View
++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `infoblox.bloxone collection <https://galaxy.ansible.com/ui/repo/published/infoblox/bloxone/>`_ (version 2.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install infoblox.bloxone`.

    To use it in a playbook, specify: :code:`infoblox.bloxone.dns_view_info`.

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

- Manage View


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

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__parameter-api_key:
      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__parameter-bloxone_api_key:

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

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__parameter-bloxone_csp_url:
      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__parameter-csp_url:

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

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__parameter-filter_query:

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

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__parameter-filters:

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

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__parameter-id:

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

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__parameter-inherit:

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

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__parameter-tag_filter_query:

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

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__parameter-tag_filters:

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

    - name: Get View information by ID
      infoblox.bloxone.dns_view_info:
        id: "{{ view_id }}"

    - name: Get View information by filters (e.g. name)
      infoblox.bloxone.dns_view_info:
        filters:
          name: "my-view"

    - name: Get View information by raw filter query
      infoblox.bloxone.dns_view_info:
        filter_query: "name=='my-view'"

    - name: Get View information by tag filters
      infoblox.bloxone.dns_view_info:
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

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-id:

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

      ID of the View object


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects"></div>

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects:

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

      View object


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/add_edns_option_in_outgoing_query"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/add_edns_option_in_outgoing_query:

      .. rst-class:: ansible-option-title

      **add_edns_option_in_outgoing_query**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/add_edns_option_in_outgoing_query" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      :emphasis:`add\_edns\_option\_in\_outgoing\_query` adds client IP, MAC address and view name into outgoing recursive query. Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/comment"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/comment:

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

      Optional. Comment for view.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/created_at"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/created_at:

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

      The timestamp when the object has been created.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/custom_root_ns"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/custom_root_ns:

      .. rst-class:: ansible-option-title

      **custom_root_ns**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/custom_root_ns" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. List of custom root nameservers. The order does not matter.

      Error if empty while :emphasis:`custom\_root\_ns\_enabled` is :emphasis:`true`. Error if there are duplicate items in the list.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/custom_root_ns/address"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/custom_root_ns/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/custom_root_ns/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      IPv4 address.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/custom_root_ns/fqdn"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/custom_root_ns/fqdn:

      .. rst-class:: ansible-option-title

      **fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/custom_root_ns/fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/custom_root_ns/protocol_fqdn"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/custom_root_ns/protocol_fqdn:

      .. rst-class:: ansible-option-title

      **protocol_fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/custom_root_ns/protocol_fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      FQDN in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/custom_root_ns_enabled"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/custom_root_ns_enabled:

      .. rst-class:: ansible-option-title

      **custom_root_ns_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/custom_root_ns_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. :emphasis:`true` to use custom root nameservers instead of the default ones.

      The :emphasis:`custom\_root\_ns` is validated when enabled.

      Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/disabled"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/disabled:

      .. rst-class:: ansible-option-title

      **disabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/disabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. :emphasis:`true` to disable object. A disabled object is effectively non-existent when generating configuration.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_enable_validation"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_enable_validation:

      .. rst-class:: ansible-option-title

      **dnssec_enable_validation**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_enable_validation" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. :emphasis:`true` to perform DNSSEC validation. Ignored if :emphasis:`dnssec\_enabled` is :emphasis:`false`.

      Defaults to :emphasis:`true`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_enabled"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_enabled:

      .. rst-class:: ansible-option-title

      **dnssec_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Master toggle for all DNSSEC processing. Other :emphasis:`dnssec`\ \*\_ configuration is unused if this is disabled.

      Defaults to :emphasis:`true`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_root_keys"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_root_keys:

      .. rst-class:: ansible-option-title

      **dnssec_root_keys**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_root_keys" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      DNSSEC root keys. The root keys are not configurable.

      A default list is provided by cloud management and included here for config generation.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_root_keys/algorithm"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_root_keys/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_root_keys/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">




      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_root_keys/protocol_zone"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_root_keys/protocol_zone:

      .. rst-class:: ansible-option-title

      **protocol_zone**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_root_keys/protocol_zone" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone FQDN in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_root_keys/public_key"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_root_keys/public_key:

      .. rst-class:: ansible-option-title

      **public_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_root_keys/public_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      DNSSEC key data. Non-empty, valid base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_root_keys/sep"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_root_keys/sep:

      .. rst-class:: ansible-option-title

      **sep**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_root_keys/sep" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Secure Entry Point flag.

      Defaults to :emphasis:`true`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_root_keys/zone"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_root_keys/zone:

      .. rst-class:: ansible-option-title

      **zone**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_root_keys/zone" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_trust_anchors"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_trust_anchors:

      .. rst-class:: ansible-option-title

      **dnssec_trust_anchors**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_trust_anchors" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. DNSSEC trust anchors.

      Error if there are list items with duplicate (\ :emphasis:`zone`\ , :emphasis:`sep`\ , :emphasis:`algorithm`\ ) combinations.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_trust_anchors/algorithm"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_trust_anchors/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_trust_anchors/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">




      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_trust_anchors/protocol_zone"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_trust_anchors/protocol_zone:

      .. rst-class:: ansible-option-title

      **protocol_zone**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_trust_anchors/protocol_zone" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone FQDN in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_trust_anchors/public_key"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_trust_anchors/public_key:

      .. rst-class:: ansible-option-title

      **public_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_trust_anchors/public_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      DNSSEC key data. Non-empty, valid base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_trust_anchors/sep"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_trust_anchors/sep:

      .. rst-class:: ansible-option-title

      **sep**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_trust_anchors/sep" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Secure Entry Point flag.

      Defaults to :emphasis:`true`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_trust_anchors/zone"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_trust_anchors/zone:

      .. rst-class:: ansible-option-title

      **zone**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_trust_anchors/zone" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dnssec_validate_expiry"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dnssec_validate_expiry:

      .. rst-class:: ansible-option-title

      **dnssec_validate_expiry**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dnssec_validate_expiry" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. :emphasis:`true` to reject expired DNSSEC keys. Ignored if either :emphasis:`dnssec\_enabled` or :emphasis:`dnssec\_enable\_validation` is :emphasis:`false`.

      Defaults to :emphasis:`true`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dtc_config"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dtc_config:

      .. rst-class:: ansible-option-title

      **dtc_config**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dtc_config" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. DTC configuration.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/dtc_config/default_ttl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/dtc_config/default_ttl:

      .. rst-class:: ansible-option-title

      **default_ttl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/dtc_config/default_ttl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Default TTL for synthesized DTC records (value in seconds).

      Defaults to 300.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ecs_enabled"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/ecs_enabled:

      .. rst-class:: ansible-option-title

      **ecs_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ecs_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. :emphasis:`true` to enable EDNS client subnet for recursive queries. Other :emphasis:`ecs`\ \*\_ fields are ignored if this field is not enabled.

      Defaults to \_false-.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ecs_forwarding"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/ecs_forwarding:

      .. rst-class:: ansible-option-title

      **ecs_forwarding**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ecs_forwarding" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. :emphasis:`true` to enable ECS options in outbound queries. This functionality has additional overhead so it is disabled by default.

      Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ecs_prefix_v4"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/ecs_prefix_v4:

      .. rst-class:: ansible-option-title

      **ecs_prefix_v4**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ecs_prefix_v4" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Maximum scope length for v4 ECS.

      Unsigned integer, min 1 max 24

      Defaults to 24.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ecs_prefix_v6"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/ecs_prefix_v6:

      .. rst-class:: ansible-option-title

      **ecs_prefix_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ecs_prefix_v6" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Maximum scope length for v6 ECS.

      Unsigned integer, min 1 max 56

      Defaults to 56.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ecs_zones"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/ecs_zones:

      .. rst-class:: ansible-option-title

      **ecs_zones**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ecs_zones" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. List of zones where ECS queries may be sent.

      Error if empty while :emphasis:`ecs\_enabled` is :emphasis:`true`. Error if there are duplicate FQDNs in the list.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ecs_zones/access"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/ecs_zones/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ecs_zones/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access control for zone.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ecs_zones/fqdn"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/ecs_zones/fqdn:

      .. rst-class:: ansible-option-title

      **fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ecs_zones/fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ecs_zones/protocol_fqdn"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/ecs_zones/protocol_fqdn:

      .. rst-class:: ansible-option-title

      **protocol_fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ecs_zones/protocol_fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone FQDN in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/edns_udp_size"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/edns_udp_size:

      .. rst-class:: ansible-option-title

      **edns_udp_size**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/edns_udp_size" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. :emphasis:`edns\_udp\_size` represents the edns UDP size. The size a querying DNS server advertises to the DNS server it&#x27;s sending a query to.

      Defaults to 1232 bytes.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_acl"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_acl:

      .. rst-class:: ansible-option-title

      **filter_aaaa_acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_acl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Specifies a list of client addresses for which AAAA filtering is to be applied.

      Defaults to :emphasis:`empty`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_acl/access"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_acl/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_acl/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access permission for :emphasis:`element`.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_acl/acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_acl/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_acl/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_acl/address"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_acl/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_acl/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Data for :emphasis:`ip` :emphasis:`element`.

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_acl/element"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_acl/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_acl/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,

      \* :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_acl/tsig_key"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_acl/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_acl/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Must be empty if :emphasis:`element` is not :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_acl/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_acl/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_acl/tsig_key/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key algorithm.

      Possible values:

      \* :emphasis:`hmac\_sha256`\ ,

      \* :emphasis:`hmac\_sha1`\ ,

      \* :emphasis:`hmac\_sha224`\ ,

      \* :emphasis:`hmac\_sha384`\ ,

      \* :emphasis:`hmac\_sha512`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_acl/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_acl/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_acl/tsig_key/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Comment for TSIG key.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_acl/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_acl/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_acl/tsig_key/key" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_acl/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_acl/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_acl/tsig_key/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name, FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_acl/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_acl/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_acl/tsig_key/protocol_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_acl/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_acl/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_acl/tsig_key/secret" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key secret, base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/filter_aaaa_on_v4"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/filter_aaaa_on_v4:

      .. rst-class:: ansible-option-title

      **filter_aaaa_on_v4**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/filter_aaaa_on_v4" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      :emphasis:`filter\_aaaa\_on\_v4` allows named to omit some IPv6 addresses when responding to IPv4 clients.

      Allowed values:

      \* :emphasis:`yes`\ ,

      \* :emphasis:`no`\ ,

      \* :emphasis:`break\_dnssec`.

      Defaults to :emphasis:`no`


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/forwarders"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/forwarders:

      .. rst-class:: ansible-option-title

      **forwarders**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/forwarders" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. List of forwarders.

      Error if empty while :emphasis:`forwarders\_only` or :emphasis:`use\_root\_forwarders\_for\_local\_resolution\_with\_b1td` is :emphasis:`true`. Error if there are items in the list with duplicate addresses.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/forwarders/address"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/forwarders/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/forwarders/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Server IP address.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/forwarders/fqdn"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/forwarders/fqdn:

      .. rst-class:: ansible-option-title

      **fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/forwarders/fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Server FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/forwarders/protocol_fqdn"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/forwarders/protocol_fqdn:

      .. rst-class:: ansible-option-title

      **protocol_fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/forwarders/protocol_fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Server FQDN in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/forwarders_only"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/forwarders_only:

      .. rst-class:: ansible-option-title

      **forwarders_only**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/forwarders_only" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. :emphasis:`true` to only forward.

      Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/gss_tsig_enabled"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/gss_tsig_enabled:

      .. rst-class:: ansible-option-title

      **gss_tsig_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/gss_tsig_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      :emphasis:`gss\_tsig\_enabled` enables/disables GSS-TSIG signed dynamic updates.

      Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/id"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/id:

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources:

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

      Optional. Inheritance configuration.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/add_edns_option_in_outgoing_query"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/add_edns_option_in_outgoing_query:

      .. rst-class:: ansible-option-title

      **add_edns_option_in_outgoing_query**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/add_edns_option_in_outgoing_query" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Field config for :emphasis:`add\_edns\_option\_in\_outgoing\_query` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/add_edns_option_in_outgoing_query/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/add_edns_option_in_outgoing_query/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/add_edns_option_in_outgoing_query/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/add_edns_option_in_outgoing_query/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/add_edns_option_in_outgoing_query/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/add_edns_option_in_outgoing_query/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/add_edns_option_in_outgoing_query/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/add_edns_option_in_outgoing_query/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/add_edns_option_in_outgoing_query/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/add_edns_option_in_outgoing_query/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/add_edns_option_in_outgoing_query/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/add_edns_option_in_outgoing_query/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/custom_root_ns_block"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/custom_root_ns_block:

      .. rst-class:: ansible-option-title

      **custom_root_ns_block**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/custom_root_ns_block" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`custom\_root\_ns\_block` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/custom_root_ns_block/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/custom_root_ns_block/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/custom_root_ns_block/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/custom_root_ns_block/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/custom_root_ns_block/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/custom_root_ns_block/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/custom_root_ns_block/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/custom_root_ns_block/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/custom_root_ns_block/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/custom_root_ns_block/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/custom_root_ns_block/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/custom_root_ns_block/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns:

      .. rst-class:: ansible-option-title

      **custom_root_ns**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`custom\_root\_ns` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns/address"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      IPv4 address.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns/fqdn"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns/fqdn:

      .. rst-class:: ansible-option-title

      **fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns/fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns/protocol_fqdn"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns/protocol_fqdn:

      .. rst-class:: ansible-option-title

      **protocol_fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns/protocol_fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      FQDN in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns_enabled"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns_enabled:

      .. rst-class:: ansible-option-title

      **custom_root_ns_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/custom_root_ns_block/value/custom_root_ns_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`custom\_root\_ns\_enabled` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block:

      .. rst-class:: ansible-option-title

      **dnssec_validation_block**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`dnssec\_validation\_block` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_enable_validation"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_enable_validation:

      .. rst-class:: ansible-option-title

      **dnssec_enable_validation**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_enable_validation" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`dnssec\_enable\_validation` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_enabled"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_enabled:

      .. rst-class:: ansible-option-title

      **dnssec_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`dnssec\_enabled` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors:

      .. rst-class:: ansible-option-title

      **dnssec_trust_anchors**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`dnssec\_trust\_anchors` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/algorithm"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">




      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/protocol_zone"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/protocol_zone:

      .. rst-class:: ansible-option-title

      **protocol_zone**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/protocol_zone" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone FQDN in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/public_key"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/public_key:

      .. rst-class:: ansible-option-title

      **public_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/public_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      DNSSEC key data. Non-empty, valid base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/sep"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/sep:

      .. rst-class:: ansible-option-title

      **sep**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/sep" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Secure Entry Point flag.

      Defaults to :emphasis:`true`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/zone"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/zone:

      .. rst-class:: ansible-option-title

      **zone**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_trust_anchors/zone" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_validate_expiry"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_validate_expiry:

      .. rst-class:: ansible-option-title

      **dnssec_validate_expiry**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dnssec_validation_block/value/dnssec_validate_expiry" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`dnssec\_validate\_expiry` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dtc_config"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dtc_config:

      .. rst-class:: ansible-option-title

      **dtc_config**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dtc_config" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`dtc\_config` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dtc_config/default_ttl"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dtc_config/default_ttl:

      .. rst-class:: ansible-option-title

      **default_ttl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dtc_config/default_ttl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`default\_ttl` field from :emphasis:`DTCConfig` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dtc_config/default_ttl/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dtc_config/default_ttl/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dtc_config/default_ttl/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dtc_config/default_ttl/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dtc_config/default_ttl/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dtc_config/default_ttl/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dtc_config/default_ttl/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dtc_config/default_ttl/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dtc_config/default_ttl/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/dtc_config/default_ttl/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/dtc_config/default_ttl/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/dtc_config/default_ttl/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block:

      .. rst-class:: ansible-option-title

      **ecs_block**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`ecs\_block` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block/value/ecs_enabled"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block/value/ecs_enabled:

      .. rst-class:: ansible-option-title

      **ecs_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block/value/ecs_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`ecs\_enabled` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block/value/ecs_forwarding"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block/value/ecs_forwarding:

      .. rst-class:: ansible-option-title

      **ecs_forwarding**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block/value/ecs_forwarding" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`ecs\_forwarding` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block/value/ecs_prefix_v4"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block/value/ecs_prefix_v4:

      .. rst-class:: ansible-option-title

      **ecs_prefix_v4**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block/value/ecs_prefix_v4" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`ecs\_prefix\_v4` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block/value/ecs_prefix_v6"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block/value/ecs_prefix_v6:

      .. rst-class:: ansible-option-title

      **ecs_prefix_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block/value/ecs_prefix_v6" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`ecs\_prefix\_v6` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block/value/ecs_zones"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block/value/ecs_zones:

      .. rst-class:: ansible-option-title

      **ecs_zones**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block/value/ecs_zones" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`ecs\_zones` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block/value/ecs_zones/access"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block/value/ecs_zones/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block/value/ecs_zones/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access control for zone.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block/value/ecs_zones/fqdn"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block/value/ecs_zones/fqdn:

      .. rst-class:: ansible-option-title

      **fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block/value/ecs_zones/fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/ecs_block/value/ecs_zones/protocol_fqdn"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/ecs_block/value/ecs_zones/protocol_fqdn:

      .. rst-class:: ansible-option-title

      **protocol_fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/ecs_block/value/ecs_zones/protocol_fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone FQDN in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>





  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/edns_udp_size"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/edns_udp_size:

      .. rst-class:: ansible-option-title

      **edns_udp_size**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/edns_udp_size" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`edns\_udp\_size` field from [View] object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/edns_udp_size/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/edns_udp_size/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/edns_udp_size/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/edns_udp_size/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/edns_udp_size/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/edns_udp_size/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/edns_udp_size/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/edns_udp_size/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/edns_udp_size/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/edns_udp_size/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/edns_udp_size/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/edns_udp_size/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl:

      .. rst-class:: ansible-option-title

      **filter_aaaa_acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`filter\_aaaa\_acl` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Inheritance setting for a field. Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/value/access"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/value/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/value/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access permission for :emphasis:`element`.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/value/acl"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/value/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/value/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/value/address"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/value/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/value/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Data for :emphasis:`ip` :emphasis:`element`.

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/value/element"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/value/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/value/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,

      \* :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Must be empty if :emphasis:`element` is not :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key algorithm.

      Possible values:

      \* :emphasis:`hmac\_sha256`\ ,

      \* :emphasis:`hmac\_sha1`\ ,

      \* :emphasis:`hmac\_sha224`\ ,

      \* :emphasis:`hmac\_sha384`\ ,

      \* :emphasis:`hmac\_sha512`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Comment for TSIG key.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/key" title="Permalink to this return value"></a>

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

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name, FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/protocol_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_acl/value/tsig_key/secret" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key secret, base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>





  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_on_v4"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_on_v4:

      .. rst-class:: ansible-option-title

      **filter_aaaa_on_v4**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_on_v4" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`filter\_aaaa\_on\_v4` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_on_v4/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_on_v4/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_on_v4/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_on_v4/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_on_v4/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_on_v4/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_on_v4/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_on_v4/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_on_v4/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/filter_aaaa_on_v4/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/filter_aaaa_on_v4/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/filter_aaaa_on_v4/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/forwarders_block"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/forwarders_block:

      .. rst-class:: ansible-option-title

      **forwarders_block**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/forwarders_block" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`forwarders\_block` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/forwarders_block/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/forwarders_block/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/forwarders_block/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/forwarders_block/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/forwarders_block/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/forwarders_block/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/forwarders_block/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/forwarders_block/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/forwarders_block/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/forwarders_block/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/forwarders_block/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/forwarders_block/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/forwarders_block/value/forwarders"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/forwarders_block/value/forwarders:

      .. rst-class:: ansible-option-title

      **forwarders**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/forwarders_block/value/forwarders" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`forwarders` field from.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/forwarders_block/value/forwarders/address"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/forwarders_block/value/forwarders/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/forwarders_block/value/forwarders/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Server IP address.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/forwarders_block/value/forwarders/fqdn"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/forwarders_block/value/forwarders/fqdn:

      .. rst-class:: ansible-option-title

      **fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/forwarders_block/value/forwarders/fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Server FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/forwarders_block/value/forwarders/protocol_fqdn"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/forwarders_block/value/forwarders/protocol_fqdn:

      .. rst-class:: ansible-option-title

      **protocol_fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/forwarders_block/value/forwarders/protocol_fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Server FQDN in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/forwarders_block/value/forwarders_only"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/forwarders_block/value/forwarders_only:

      .. rst-class:: ansible-option-title

      **forwarders_only**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/forwarders_block/value/forwarders_only" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`forwarders\_only` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/forwarders_block/value/use_root_forwarders_for_local_resolution_with_b1td"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/forwarders_block/value/use_root_forwarders_for_local_resolution_with_b1td:

      .. rst-class:: ansible-option-title

      **use_root_forwarders_for_local_resolution_with_b1td**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/forwarders_block/value/use_root_forwarders_for_local_resolution_with_b1td" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`use\_root\_forwarders\_for\_local\_resolution\_with\_b1td` field.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/gss_tsig_enabled"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/gss_tsig_enabled:

      .. rst-class:: ansible-option-title

      **gss_tsig_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/gss_tsig_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`gss\_tsig\_enabled` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/gss_tsig_enabled/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/gss_tsig_enabled/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/gss_tsig_enabled/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/gss_tsig_enabled/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/gss_tsig_enabled/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/gss_tsig_enabled/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/gss_tsig_enabled/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/gss_tsig_enabled/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/gss_tsig_enabled/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/gss_tsig_enabled/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/gss_tsig_enabled/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/gss_tsig_enabled/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/lame_ttl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/lame_ttl:

      .. rst-class:: ansible-option-title

      **lame_ttl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/lame_ttl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`lame\_ttl` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/lame_ttl/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/lame_ttl/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/lame_ttl/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/lame_ttl/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/lame_ttl/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/lame_ttl/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/lame_ttl/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/lame_ttl/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/lame_ttl/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/lame_ttl/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/lame_ttl/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/lame_ttl/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/match_recursive_only"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/match_recursive_only:

      .. rst-class:: ansible-option-title

      **match_recursive_only**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/match_recursive_only" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`match\_recursive\_only` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/match_recursive_only/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/match_recursive_only/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/match_recursive_only/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/match_recursive_only/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/match_recursive_only/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/match_recursive_only/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/match_recursive_only/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/match_recursive_only/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/match_recursive_only/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/match_recursive_only/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/match_recursive_only/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/match_recursive_only/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_cache_ttl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_cache_ttl:

      .. rst-class:: ansible-option-title

      **max_cache_ttl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_cache_ttl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`max\_cache\_ttl` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_cache_ttl/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_cache_ttl/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_cache_ttl/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_cache_ttl/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_cache_ttl/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_cache_ttl/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_cache_ttl/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_cache_ttl/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_cache_ttl/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_cache_ttl/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_cache_ttl/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_cache_ttl/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_negative_ttl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_negative_ttl:

      .. rst-class:: ansible-option-title

      **max_negative_ttl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_negative_ttl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`max\_negative\_ttl` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_negative_ttl/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_negative_ttl/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_negative_ttl/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_negative_ttl/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_negative_ttl/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_negative_ttl/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_negative_ttl/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_negative_ttl/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_negative_ttl/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_negative_ttl/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_negative_ttl/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_negative_ttl/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_udp_size"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_udp_size:

      .. rst-class:: ansible-option-title

      **max_udp_size**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_udp_size" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`max\_udp\_size` field from [View] object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_udp_size/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_udp_size/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_udp_size/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_udp_size/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_udp_size/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_udp_size/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_udp_size/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_udp_size/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_udp_size/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/max_udp_size/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/max_udp_size/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/max_udp_size/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/minimal_responses"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/minimal_responses:

      .. rst-class:: ansible-option-title

      **minimal_responses**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/minimal_responses" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`minimal\_responses` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/minimal_responses/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/minimal_responses/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/minimal_responses/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/minimal_responses/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/minimal_responses/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/minimal_responses/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/minimal_responses/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/minimal_responses/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/minimal_responses/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/minimal_responses/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/minimal_responses/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/minimal_responses/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/notify"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/notify:

      .. rst-class:: ansible-option-title

      **notify**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/notify" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Field config for :emphasis:`notify` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/notify/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/notify/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/notify/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/notify/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/notify/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/notify/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/notify/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/notify/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/notify/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/notify/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/notify/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/notify/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl:

      .. rst-class:: ansible-option-title

      **query_acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`query\_acl` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Inheritance setting for a field. Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/value/access"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/value/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/value/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access permission for :emphasis:`element`.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/value/acl"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/value/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/value/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/value/address"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/value/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/value/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Data for :emphasis:`ip` :emphasis:`element`.

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/value/element"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/value/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/value/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,

      \* :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/value/tsig_key"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/value/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Must be empty if :emphasis:`element` is not :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/value/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/value/tsig_key/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key algorithm.

      Possible values:

      \* :emphasis:`hmac\_sha256`\ ,

      \* :emphasis:`hmac\_sha1`\ ,

      \* :emphasis:`hmac\_sha224`\ ,

      \* :emphasis:`hmac\_sha384`\ ,

      \* :emphasis:`hmac\_sha512`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/value/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/value/tsig_key/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Comment for TSIG key.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/value/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/value/tsig_key/key" title="Permalink to this return value"></a>

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

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/value/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/value/tsig_key/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name, FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/value/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/value/tsig_key/protocol_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/value/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/query_acl/value/tsig_key/secret" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key secret, base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>





  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl:

      .. rst-class:: ansible-option-title

      **recursion_acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`recursion\_acl` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Inheritance setting for a field. Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/value/access"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/value/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/value/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access permission for :emphasis:`element`.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/value/acl"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/value/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/value/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/value/address"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/value/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/value/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Data for :emphasis:`ip` :emphasis:`element`.

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/value/element"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/value/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/value/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,

      \* :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/value/tsig_key"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/value/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/value/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Must be empty if :emphasis:`element` is not :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/value/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/value/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/value/tsig_key/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key algorithm.

      Possible values:

      \* :emphasis:`hmac\_sha256`\ ,

      \* :emphasis:`hmac\_sha1`\ ,

      \* :emphasis:`hmac\_sha224`\ ,

      \* :emphasis:`hmac\_sha384`\ ,

      \* :emphasis:`hmac\_sha512`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/value/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/value/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/value/tsig_key/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Comment for TSIG key.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/value/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/value/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/value/tsig_key/key" title="Permalink to this return value"></a>

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

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/value/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/value/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/value/tsig_key/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name, FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/value/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/value/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/value/tsig_key/protocol_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_acl/value/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_acl/value/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_acl/value/tsig_key/secret" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key secret, base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>





  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_enabled"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_enabled:

      .. rst-class:: ansible-option-title

      **recursion_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`recursion\_enabled` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_enabled/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_enabled/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_enabled/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_enabled/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_enabled/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_enabled/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_enabled/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_enabled/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_enabled/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/recursion_enabled/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/recursion_enabled/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/recursion_enabled/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/sort_list"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/sort_list:

      .. rst-class:: ansible-option-title

      **sort_list**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/sort_list" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`sort\_list` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/sort_list/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/sort_list/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/sort_list/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Inheritance setting for a field. Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/sort_list/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/sort_list/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/sort_list/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/sort_list/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/sort_list/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/sort_list/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/sort_list/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/sort_list/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/sort_list/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/sort_list/value/acl"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/sort_list/value/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/sort_list/value/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/sort_list/value/element"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/sort_list/value/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/sort_list/value/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/sort_list/value/prioritized_networks"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/sort_list/value/prioritized_networks:

      .. rst-class:: ansible-option-title

      **prioritized_networks**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/sort_list/value/prioritized_networks" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. The prioritized networks. If empty, the value of :emphasis:`source` or networks from :emphasis:`acl` is used.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/sort_list/value/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/sort_list/value/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/sort_list/value/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/synthesize_address_records_from_https"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/synthesize_address_records_from_https:

      .. rst-class:: ansible-option-title

      **synthesize_address_records_from_https**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/synthesize_address_records_from_https" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Field config for :emphasis:`synthesize\_address\_records\_from\_https` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/synthesize_address_records_from_https/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/synthesize_address_records_from_https/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/synthesize_address_records_from_https/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/synthesize_address_records_from_https/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/synthesize_address_records_from_https/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/synthesize_address_records_from_https/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/synthesize_address_records_from_https/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/synthesize_address_records_from_https/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/synthesize_address_records_from_https/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/synthesize_address_records_from_https/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/synthesize_address_records_from_https/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/synthesize_address_records_from_https/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl:

      .. rst-class:: ansible-option-title

      **transfer_acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`transfer\_acl` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Inheritance setting for a field. Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/value/access"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/value/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/value/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access permission for :emphasis:`element`.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/value/acl"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/value/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/value/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/value/address"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/value/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/value/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Data for :emphasis:`ip` :emphasis:`element`.

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/value/element"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/value/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/value/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,

      \* :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/value/tsig_key"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/value/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Must be empty if :emphasis:`element` is not :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/value/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/value/tsig_key/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key algorithm.

      Possible values:

      \* :emphasis:`hmac\_sha256`\ ,

      \* :emphasis:`hmac\_sha1`\ ,

      \* :emphasis:`hmac\_sha224`\ ,

      \* :emphasis:`hmac\_sha384`\ ,

      \* :emphasis:`hmac\_sha512`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/value/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/value/tsig_key/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Comment for TSIG key.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/value/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/value/tsig_key/key" title="Permalink to this return value"></a>

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

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/value/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/value/tsig_key/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name, FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/value/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/value/tsig_key/protocol_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/value/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/transfer_acl/value/tsig_key/secret" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key secret, base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>





  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl:

      .. rst-class:: ansible-option-title

      **update_acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`update\_acl` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Inheritance setting for a field. Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/value/access"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/value/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/value/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access permission for :emphasis:`element`.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/value/acl"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/value/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/value/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/value/address"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/value/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/value/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Data for :emphasis:`ip` :emphasis:`element`.

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/value/element"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/value/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/value/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,

      \* :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/value/tsig_key"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/value/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Must be empty if :emphasis:`element` is not :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/value/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/value/tsig_key/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key algorithm.

      Possible values:

      \* :emphasis:`hmac\_sha256`\ ,

      \* :emphasis:`hmac\_sha1`\ ,

      \* :emphasis:`hmac\_sha224`\ ,

      \* :emphasis:`hmac\_sha384`\ ,

      \* :emphasis:`hmac\_sha512`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/value/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/value/tsig_key/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Comment for TSIG key.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/value/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/value/tsig_key/key" title="Permalink to this return value"></a>

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

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/value/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/value/tsig_key/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name, FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/value/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/value/tsig_key/protocol_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/value/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/update_acl/value/tsig_key/secret" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key secret, base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>





  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/use_forwarders_for_subzones"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/use_forwarders_for_subzones:

      .. rst-class:: ansible-option-title

      **use_forwarders_for_subzones**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/use_forwarders_for_subzones" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`use\_forwarders\_for\_subzones` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/use_forwarders_for_subzones/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/use_forwarders_for_subzones/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/use_forwarders_for_subzones/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/use_forwarders_for_subzones/display_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/use_forwarders_for_subzones/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/use_forwarders_for_subzones/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/use_forwarders_for_subzones/source"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/use_forwarders_for_subzones/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/use_forwarders_for_subzones/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/use_forwarders_for_subzones/value"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/use_forwarders_for_subzones/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/use_forwarders_for_subzones/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority:

      .. rst-class:: ansible-option-title

      **zone_authority**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`zone\_authority` field from :emphasis:`View` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/default_ttl"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/default_ttl:

      .. rst-class:: ansible-option-title

      **default_ttl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/default_ttl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`default\_ttl` field from :emphasis:`ZoneAuthority` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/default_ttl/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/default_ttl/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/default_ttl/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/default_ttl/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/default_ttl/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/default_ttl/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/default_ttl/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/default_ttl/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/default_ttl/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/default_ttl/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/default_ttl/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/default_ttl/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/expire"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/expire:

      .. rst-class:: ansible-option-title

      **expire**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/expire" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`expire` field from :emphasis:`ZoneAuthority` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/expire/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/expire/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/expire/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/expire/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/expire/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/expire/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/expire/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/expire/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/expire/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/expire/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/expire/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/expire/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/mname_block"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/mname_block:

      .. rst-class:: ansible-option-title

      **mname_block**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/mname_block" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`mname` block from :emphasis:`ZoneAuthority` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/mname_block/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/mname_block/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/mname_block/action" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Defaults to :emphasis:`inherit`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/mname_block/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/mname_block/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/mname_block/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Human-readable display name for the object referred to by :emphasis:`source`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/mname_block/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/mname_block/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/mname_block/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/mname_block/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/mname_block/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/mname_block/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Inherited value.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/mname_block/value/mname"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/mname_block/value/mname:

      .. rst-class:: ansible-option-title

      **mname**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/mname_block/value/mname" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/mname_block/value/protocol_mname"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/mname_block/value/protocol_mname:

      .. rst-class:: ansible-option-title

      **protocol_mname**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/mname_block/value/protocol_mname" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Master name server in punycode.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/mname_block/value/use_default_mname"></div>

      .. raw:: latex

        \hspace{0.1\textwidth}\begin{minipage}[t]{0.22\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/mname_block/value/use_default_mname:

      .. rst-class:: ansible-option-title

      **use_default_mname**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/mname_block/value/use_default_mname" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Use default value for master name server.

      Defaults to true.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/negative_ttl"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/negative_ttl:

      .. rst-class:: ansible-option-title

      **negative_ttl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/negative_ttl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`negative\_ttl` field from :emphasis:`ZoneAuthority` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/negative_ttl/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/negative_ttl/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/negative_ttl/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/negative_ttl/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/negative_ttl/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/negative_ttl/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/negative_ttl/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/negative_ttl/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/negative_ttl/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/negative_ttl/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/negative_ttl/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/negative_ttl/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/protocol_rname"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/protocol_rname:

      .. rst-class:: ansible-option-title

      **protocol_rname**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/protocol_rname" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`protocol\_rname` field from :emphasis:`ZoneAuthority` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/protocol_rname/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/protocol_rname/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/protocol_rname/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/protocol_rname/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/protocol_rname/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/protocol_rname/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/protocol_rname/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/protocol_rname/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/protocol_rname/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/protocol_rname/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/protocol_rname/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/protocol_rname/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/refresh"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/refresh:

      .. rst-class:: ansible-option-title

      **refresh**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/refresh" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`refresh` field from :emphasis:`ZoneAuthority` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/refresh/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/refresh/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/refresh/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/refresh/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/refresh/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/refresh/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/refresh/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/refresh/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/refresh/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/refresh/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/refresh/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/refresh/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/retry"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/retry:

      .. rst-class:: ansible-option-title

      **retry**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/retry" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`retry` field from :emphasis:`ZoneAuthority` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/retry/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/retry/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/retry/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/retry/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/retry/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/retry/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/retry/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/retry/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/retry/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/retry/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/retry/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/retry/value" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/rname"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/rname:

      .. rst-class:: ansible-option-title

      **rname**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/rname" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Field config for :emphasis:`rname` field from :emphasis:`ZoneAuthority` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/rname/action"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/rname/action:

      .. rst-class:: ansible-option-title

      **action**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/rname/action" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/rname/display_name"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/rname/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/rname/display_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/rname/source"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/rname/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/rname/source" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/rname/value"></div>

      .. raw:: latex

        \hspace{0.08\textwidth}\begin{minipage}[t]{0.24\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/inheritance_sources/zone_authority/rname/value:

      .. rst-class:: ansible-option-title

      **value**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_sources/zone_authority/rname/value" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

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

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/ip_spaces"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/ip_spaces:

      .. rst-class:: ansible-option-title

      **ip_spaces**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/ip_spaces" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

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
        <div class="ansibleOptionAnchor" id="return-objects/lame_ttl"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/lame_ttl:

      .. rst-class:: ansible-option-title

      **lame_ttl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/lame_ttl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Unused in the current on-prem DNS server implementation.

      Unsigned integer, min 0 max 3600 (1h).

      Defaults to 600.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_clients_acl"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_clients_acl:

      .. rst-class:: ansible-option-title

      **match_clients_acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_clients_acl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Specifies which clients have access to the view.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_clients_acl/access"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_clients_acl/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_clients_acl/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access permission for :emphasis:`element`.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_clients_acl/acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_clients_acl/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_clients_acl/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/match_clients_acl/address"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_clients_acl/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_clients_acl/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Data for :emphasis:`ip` :emphasis:`element`.

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_clients_acl/element"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_clients_acl/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_clients_acl/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,

      \* :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_clients_acl/tsig_key"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_clients_acl/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_clients_acl/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Must be empty if :emphasis:`element` is not :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_clients_acl/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_clients_acl/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_clients_acl/tsig_key/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key algorithm.

      Possible values:

      \* :emphasis:`hmac\_sha256`\ ,

      \* :emphasis:`hmac\_sha1`\ ,

      \* :emphasis:`hmac\_sha224`\ ,

      \* :emphasis:`hmac\_sha384`\ ,

      \* :emphasis:`hmac\_sha512`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_clients_acl/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_clients_acl/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_clients_acl/tsig_key/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Comment for TSIG key.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_clients_acl/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_clients_acl/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_clients_acl/tsig_key/key" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/match_clients_acl/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_clients_acl/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_clients_acl/tsig_key/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name, FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_clients_acl/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_clients_acl/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_clients_acl/tsig_key/protocol_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_clients_acl/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_clients_acl/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_clients_acl/tsig_key/secret" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key secret, base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_destinations_acl"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_destinations_acl:

      .. rst-class:: ansible-option-title

      **match_destinations_acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_destinations_acl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Specifies which destination addresses have access to the view.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_destinations_acl/access"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_destinations_acl/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_destinations_acl/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access permission for :emphasis:`element`.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_destinations_acl/acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_destinations_acl/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_destinations_acl/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/match_destinations_acl/address"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_destinations_acl/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_destinations_acl/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Data for :emphasis:`ip` :emphasis:`element`.

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_destinations_acl/element"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_destinations_acl/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_destinations_acl/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,

      \* :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_destinations_acl/tsig_key"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_destinations_acl/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_destinations_acl/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Must be empty if :emphasis:`element` is not :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_destinations_acl/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_destinations_acl/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_destinations_acl/tsig_key/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key algorithm.

      Possible values:

      \* :emphasis:`hmac\_sha256`\ ,

      \* :emphasis:`hmac\_sha1`\ ,

      \* :emphasis:`hmac\_sha224`\ ,

      \* :emphasis:`hmac\_sha384`\ ,

      \* :emphasis:`hmac\_sha512`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_destinations_acl/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_destinations_acl/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_destinations_acl/tsig_key/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Comment for TSIG key.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_destinations_acl/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_destinations_acl/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_destinations_acl/tsig_key/key" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/match_destinations_acl/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_destinations_acl/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_destinations_acl/tsig_key/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name, FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_destinations_acl/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_destinations_acl/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_destinations_acl/tsig_key/protocol_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_destinations_acl/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_destinations_acl/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_destinations_acl/tsig_key/secret" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key secret, base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/match_recursive_only"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/match_recursive_only:

      .. rst-class:: ansible-option-title

      **match_recursive_only**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/match_recursive_only" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. If :emphasis:`true` only recursive queries from matching clients access the view.

      Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/max_cache_ttl"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/max_cache_ttl:

      .. rst-class:: ansible-option-title

      **max_cache_ttl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/max_cache_ttl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Seconds to cache positive responses.

      Unsigned integer, min 1 max 604800 (7d).

      Defaults to 604800 (7d).


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/max_negative_ttl"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/max_negative_ttl:

      .. rst-class:: ansible-option-title

      **max_negative_ttl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/max_negative_ttl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Seconds to cache negative responses.

      Unsigned integer, min 1 max 604800 (7d).

      Defaults to 10800 (3h).


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/max_udp_size"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/max_udp_size:

      .. rst-class:: ansible-option-title

      **max_udp_size**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/max_udp_size" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. :emphasis:`max\_udp\_size` represents maximum UDP payload size. The maximum number of bytes a responding DNS server will send to a UDP datagram.

      Defaults to 1232 bytes.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/minimal_responses"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/minimal_responses:

      .. rst-class:: ansible-option-title

      **minimal_responses**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/minimal_responses" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. When enabled, the DNS server will only add records to the authority and additional data sections when they are required.

      Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/name"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/name:

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

      Name of view.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/notify"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/notify:

      .. rst-class:: ansible-option-title

      **notify**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/notify" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      :emphasis:`notify` all external secondary DNS servers.

      Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/query_acl"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/query_acl:

      .. rst-class:: ansible-option-title

      **query_acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/query_acl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Clients must match this ACL to make authoritative queries. Also used for recursive queries if that ACL is unset.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/query_acl/access"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/query_acl/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/query_acl/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access permission for :emphasis:`element`.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/query_acl/acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/query_acl/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/query_acl/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/query_acl/address"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/query_acl/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/query_acl/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Data for :emphasis:`ip` :emphasis:`element`.

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/query_acl/element"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/query_acl/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/query_acl/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,

      \* :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/query_acl/tsig_key"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/query_acl/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/query_acl/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Must be empty if :emphasis:`element` is not :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/query_acl/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/query_acl/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/query_acl/tsig_key/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key algorithm.

      Possible values:

      \* :emphasis:`hmac\_sha256`\ ,

      \* :emphasis:`hmac\_sha1`\ ,

      \* :emphasis:`hmac\_sha224`\ ,

      \* :emphasis:`hmac\_sha384`\ ,

      \* :emphasis:`hmac\_sha512`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/query_acl/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/query_acl/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/query_acl/tsig_key/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Comment for TSIG key.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/query_acl/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/query_acl/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/query_acl/tsig_key/key" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/query_acl/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/query_acl/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/query_acl/tsig_key/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name, FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/query_acl/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/query_acl/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/query_acl/tsig_key/protocol_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/query_acl/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/query_acl/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/query_acl/tsig_key/secret" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key secret, base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/recursion_acl"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_acl:

      .. rst-class:: ansible-option-title

      **recursion_acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_acl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Clients must match this ACL to make recursive queries. If this ACL is empty, then the :emphasis:`query\_acl` will be used instead.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/recursion_acl/access"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_acl/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_acl/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access permission for :emphasis:`element`.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/recursion_acl/acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_acl/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_acl/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/recursion_acl/address"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_acl/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_acl/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Data for :emphasis:`ip` :emphasis:`element`.

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/recursion_acl/element"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_acl/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_acl/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,

      \* :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/recursion_acl/tsig_key"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_acl/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_acl/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Must be empty if :emphasis:`element` is not :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/recursion_acl/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_acl/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_acl/tsig_key/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key algorithm.

      Possible values:

      \* :emphasis:`hmac\_sha256`\ ,

      \* :emphasis:`hmac\_sha1`\ ,

      \* :emphasis:`hmac\_sha224`\ ,

      \* :emphasis:`hmac\_sha384`\ ,

      \* :emphasis:`hmac\_sha512`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/recursion_acl/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_acl/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_acl/tsig_key/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Comment for TSIG key.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/recursion_acl/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_acl/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_acl/tsig_key/key" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/recursion_acl/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_acl/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_acl/tsig_key/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name, FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/recursion_acl/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_acl/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_acl/tsig_key/protocol_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/recursion_acl/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_acl/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_acl/tsig_key/secret" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key secret, base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/recursion_enabled"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/recursion_enabled:

      .. rst-class:: ansible-option-title

      **recursion_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/recursion_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. :emphasis:`true` to allow recursive DNS queries.

      Defaults to :emphasis:`true`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/sort_list"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/sort_list:

      .. rst-class:: ansible-option-title

      **sort_list**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/sort_list" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Specifies a sorted network list for A/AAAA records in DNS query response.

      Defaults to :emphasis:`empty`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/sort_list/acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/sort_list/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/sort_list/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/sort_list/element"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/sort_list/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/sort_list/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/sort_list/prioritized_networks"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/sort_list/prioritized_networks:

      .. rst-class:: ansible-option-title

      **prioritized_networks**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/sort_list/prioritized_networks" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. The prioritized networks. If empty, the value of :emphasis:`source` or networks from :emphasis:`acl` is used.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/sort_list/source"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/sort_list/source:

      .. rst-class:: ansible-option-title

      **source**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/sort_list/source" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/synthesize_address_records_from_https"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/synthesize_address_records_from_https:

      .. rst-class:: ansible-option-title

      **synthesize_address_records_from_https**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/synthesize_address_records_from_https" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      :emphasis:`synthesize\_address\_records\_from\_https` enables/disables creation of A/AAAA records from HTTPS RR Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/tags"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/tags:

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

      Tagging specifics.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/transfer_acl:

      .. rst-class:: ansible-option-title

      **transfer_acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/transfer_acl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Clients must match this ACL to receive zone transfers.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl/access"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/transfer_acl/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/transfer_acl/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access permission for :emphasis:`element`.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl/acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/transfer_acl/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/transfer_acl/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl/address"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/transfer_acl/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/transfer_acl/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Data for :emphasis:`ip` :emphasis:`element`.

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl/element"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/transfer_acl/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/transfer_acl/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,

      \* :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl/tsig_key"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/transfer_acl/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/transfer_acl/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Must be empty if :emphasis:`element` is not :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/transfer_acl/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/transfer_acl/tsig_key/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key algorithm.

      Possible values:

      \* :emphasis:`hmac\_sha256`\ ,

      \* :emphasis:`hmac\_sha1`\ ,

      \* :emphasis:`hmac\_sha224`\ ,

      \* :emphasis:`hmac\_sha384`\ ,

      \* :emphasis:`hmac\_sha512`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/transfer_acl/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/transfer_acl/tsig_key/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Comment for TSIG key.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/transfer_acl/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/transfer_acl/tsig_key/key" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/transfer_acl/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/transfer_acl/tsig_key/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name, FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/transfer_acl/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/transfer_acl/tsig_key/protocol_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/transfer_acl/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/transfer_acl/tsig_key/secret" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key secret, base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/update_acl"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/update_acl:

      .. rst-class:: ansible-option-title

      **update_acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/update_acl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Specifies which hosts are allowed to issue Dynamic DNS updates for authoritative zones of :emphasis:`primary\_type` :emphasis:`cloud`.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/update_acl/access"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/update_acl/access:

      .. rst-class:: ansible-option-title

      **access**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/update_acl/access" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Access permission for :emphasis:`element`.

      Allowed values:

      \* :emphasis:`allow`\ ,

      \* :emphasis:`deny`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/update_acl/acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/update_acl/acl:

      .. rst-class:: ansible-option-title

      **acl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/update_acl/acl" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/update_acl/address"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/update_acl/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/update_acl/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Data for :emphasis:`ip` :emphasis:`element`.

      Must be empty if :emphasis:`element` is not :emphasis:`ip`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/update_acl/element"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/update_acl/element:

      .. rst-class:: ansible-option-title

      **element**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/update_acl/element" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Type of element.

      Allowed values:

      \* :emphasis:`any`\ ,

      \* :emphasis:`ip`\ ,

      \* :emphasis:`acl`\ ,

      \* :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/update_acl/tsig_key"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/update_acl/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/update_acl/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Must be empty if :emphasis:`element` is not :emphasis:`tsig\_key`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/update_acl/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/update_acl/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/update_acl/tsig_key/algorithm" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key algorithm.

      Possible values:

      \* :emphasis:`hmac\_sha256`\ ,

      \* :emphasis:`hmac\_sha1`\ ,

      \* :emphasis:`hmac\_sha224`\ ,

      \* :emphasis:`hmac\_sha384`\ ,

      \* :emphasis:`hmac\_sha512`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/update_acl/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/update_acl/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/update_acl/tsig_key/comment" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Comment for TSIG key.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/update_acl/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/update_acl/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/update_acl/tsig_key/key" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/update_acl/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/update_acl/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/update_acl/tsig_key/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name, FQDN.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/update_acl/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/update_acl/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/update_acl/tsig_key/protocol_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key name in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/update_acl/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/update_acl/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/update_acl/tsig_key/secret" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key secret, base64 string.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>




  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/updated_at"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/updated_at:

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

      The timestamp when the object has been updated. Equals to :emphasis:`created\_at` if not updated after creation.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/use_forwarders_for_subzones"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/use_forwarders_for_subzones:

      .. rst-class:: ansible-option-title

      **use_forwarders_for_subzones**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/use_forwarders_for_subzones" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Use default forwarders to resolve queries for subzones.

      Defaults to :emphasis:`true`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/use_root_forwarders_for_local_resolution_with_b1td"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/use_root_forwarders_for_local_resolution_with_b1td:

      .. rst-class:: ansible-option-title

      **use_root_forwarders_for_local_resolution_with_b1td**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/use_root_forwarders_for_local_resolution_with_b1td" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      :emphasis:`use\_root\_forwarders\_for\_local\_resolution\_with\_b1td` allows DNS recursive queries sent to root forwarders for local resolution when deployed alongside BloxOne Thread Defense. Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/zone_authority"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/zone_authority:

      .. rst-class:: ansible-option-title

      **zone_authority**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/zone_authority" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. ZoneAuthority.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/zone_authority/default_ttl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/zone_authority/default_ttl:

      .. rst-class:: ansible-option-title

      **default_ttl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/zone_authority/default_ttl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. ZoneAuthority default ttl for resource records in zone (value in seconds).

      Defaults to 28800.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/zone_authority/expire"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/zone_authority/expire:

      .. rst-class:: ansible-option-title

      **expire**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/zone_authority/expire" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. ZoneAuthority expire time in seconds.

      Defaults to 2419200.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/zone_authority/mname"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/zone_authority/mname:

      .. rst-class:: ansible-option-title

      **mname**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/zone_authority/mname" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/zone_authority/negative_ttl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/zone_authority/negative_ttl:

      .. rst-class:: ansible-option-title

      **negative_ttl**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/zone_authority/negative_ttl" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. ZoneAuthority negative caching (minimum) ttl in seconds.

      Defaults to 900.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/zone_authority/protocol_mname"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/zone_authority/protocol_mname:

      .. rst-class:: ansible-option-title

      **protocol_mname**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/zone_authority/protocol_mname" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. ZoneAuthority master name server in punycode.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/zone_authority/protocol_rname"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/zone_authority/protocol_rname:

      .. rst-class:: ansible-option-title

      **protocol_rname**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/zone_authority/protocol_rname" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. A domain name which specifies the mailbox of the person responsible for this zone.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/zone_authority/refresh"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/zone_authority/refresh:

      .. rst-class:: ansible-option-title

      **refresh**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/zone_authority/refresh" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. ZoneAuthority refresh.

      Defaults to 10800.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/zone_authority/retry"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/zone_authority/retry:

      .. rst-class:: ansible-option-title

      **retry**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/zone_authority/retry" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. ZoneAuthority retry.

      Defaults to 3600.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/zone_authority/rname"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/zone_authority/rname:

      .. rst-class:: ansible-option-title

      **rname**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/zone_authority/rname" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. ZoneAuthority rname.

      Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/zone_authority/use_default_mname"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_view_info_module__return-objects/zone_authority/use_default_mname:

      .. rst-class:: ansible-option-title

      **use_default_mname**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/zone_authority/use_default_mname" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Use default value for master name server.

      Defaults to true.


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
