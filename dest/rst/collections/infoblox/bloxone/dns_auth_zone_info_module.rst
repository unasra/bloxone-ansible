.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.15.0

.. Anchors

.. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module:

.. Anchors: short name for ansible.builtin

.. Title

infoblox.bloxone.dns_auth_zone_info module -- Manage AuthZone
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This module is part of the `infoblox.bloxone collection <https://galaxy.ansible.com/ui/repo/published/infoblox/bloxone/>`_ (version 2.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it, use: :code:`ansible-galaxy collection install infoblox.bloxone`.

    To use it in a playbook, specify: :code:`infoblox.bloxone.dns_auth_zone_info`.

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

- Manage AuthZone


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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__parameter-api_key:
      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__parameter-bloxone_api_key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__parameter-bloxone_csp_url:
      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__parameter-csp_url:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__parameter-filter_query:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__parameter-filters:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__parameter-id:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__parameter-inherit:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__parameter-tag_filter_query:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__parameter-tag_filters:

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

    - name: Get Auth Zone information by ID
      infoblox.bloxone.dns_auth_zone_info:
        id: "{{ auth_zone_id }}"

    - name: Get Auth Zone information by filters (e.g. name)
      infoblox.bloxone.dns_auth_zone_info:
        filters:
          fqdn: "example_zone"

    - name: Get Auth Zone information by raw filter query
      infoblox.bloxone.dns_auth_zone_info:
        filter_query: "name=='example_zone'"

    - name: Get Auth Zone information by tag filters
      infoblox.bloxone.dns_auth_zone_info:
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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-id:

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

      ID of the AuthZone object


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects"></div>

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects:

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

      AuthZone object


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/comment"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/comment:

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

      Optional. Comment for zone configuration.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/created_at"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/created_at:

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
        <div class="ansibleOptionAnchor" id="return-objects/disabled"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/disabled:

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
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries:

      .. rst-class:: ansible-option-title

      **external_primaries**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. DNS primaries external to BloxOne DDI. Order is not significant.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/address"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Required only if :emphasis:`type` is :emphasis:`server`. IP Address of nameserver.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/fqdn"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/fqdn:

      .. rst-class:: ansible-option-title

      **fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. Required only if :emphasis:`type` is :emphasis:`server`. FQDN of nameserver.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/nsg"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/nsg:

      .. rst-class:: ansible-option-title

      **nsg**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/nsg" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/protocol_fqdn"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/protocol_fqdn:

      .. rst-class:: ansible-option-title

      **protocol_fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/protocol_fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      FQDN of nameserver in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/tsig_enabled"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/tsig_enabled:

      .. rst-class:: ansible-option-title

      **tsig_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/tsig_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. If enabled, secondaries will use the configured TSIG key when requesting a zone transfer from this primary.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/tsig_key"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. TSIG key.

      Error if empty while :emphasis:`tsig\_enabled` is :emphasis:`true`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/tsig_key/algorithm" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/tsig_key/comment" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/tsig_key/key" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/tsig_key/name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/tsig_key/protocol_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/tsig_key/secret" title="Permalink to this return value"></a>

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

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_primaries/type"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_primaries/type:

      .. rst-class:: ansible-option-title

      **type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_primaries/type" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Allowed values:

      \* :emphasis:`nsg`\ ,

      \* :emphasis:`primary`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_providers"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_providers:

      .. rst-class:: ansible-option-title

      **external_providers**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_providers" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      list of external providers for the auth zone.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_providers/id"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_providers/id:

      .. rst-class:: ansible-option-title

      **id**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_providers/id" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The identifier of the external provider.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_providers/name"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_providers/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_providers/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The name of the external provider.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_providers/type"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_providers/type:

      .. rst-class:: ansible-option-title

      **type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_providers/type" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Defines the type of external provider. Allowed values:

      \* :emphasis:`bloxone\_ddi`\ : host type is BloxOne DDI,

      \* :emphasis:`microsoft\_azure`\ : host type is Microsoft Azure,

      \* :emphasis:`amazon\_web\_service`\ : host type is Amazon Web Services,

      \* :emphasis:`microsoft\_active\_directory`\ : host type is Microsoft Active Directory,

      \* :emphasis:`google\_cloud\_platform`\ : host type is Google Cloud Platform.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries:

      .. rst-class:: ansible-option-title

      **external_secondaries**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      DNS secondaries external to BloxOne DDI. Order is not significant.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries/address"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries/address:

      .. rst-class:: ansible-option-title

      **address**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries/address" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      IP Address of nameserver.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries/fqdn"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries/fqdn:

      .. rst-class:: ansible-option-title

      **fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries/fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      FQDN of nameserver.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries/protocol_fqdn"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries/protocol_fqdn:

      .. rst-class:: ansible-option-title

      **protocol_fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries/protocol_fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      FQDN of nameserver in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries/stealth"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries/stealth:

      .. rst-class:: ansible-option-title

      **stealth**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries/stealth" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      If enabled, the NS record and glue record will NOT be automatically generated according to secondaries nameserver assignment.

      Default: :emphasis:`false`


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries/tsig_enabled"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries/tsig_enabled:

      .. rst-class:: ansible-option-title

      **tsig_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries/tsig_enabled" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`boolean`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      If enabled, secondaries will use the configured TSIG key when requesting a zone transfer.

      Default: :emphasis:`false`


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries/tsig_key"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries/tsig_key:

      .. rst-class:: ansible-option-title

      **tsig_key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries/tsig_key" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      TSIG key.

      Error if empty while :emphasis:`tsig\_enabled` is :emphasis:`true`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries/tsig_key/algorithm"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries/tsig_key/algorithm:

      .. rst-class:: ansible-option-title

      **algorithm**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries/tsig_key/algorithm" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries/tsig_key/comment"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries/tsig_key/comment:

      .. rst-class:: ansible-option-title

      **comment**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries/tsig_key/comment" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries/tsig_key/key"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries/tsig_key/key:

      .. rst-class:: ansible-option-title

      **key**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries/tsig_key/key" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries/tsig_key/name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries/tsig_key/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries/tsig_key/name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries/tsig_key/protocol_name"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries/tsig_key/protocol_name:

      .. rst-class:: ansible-option-title

      **protocol_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries/tsig_key/protocol_name" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/external_secondaries/tsig_key/secret"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/external_secondaries/tsig_key/secret:

      .. rst-class:: ansible-option-title

      **secret**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/external_secondaries/tsig_key/secret" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/fqdn"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/fqdn:

      .. rst-class:: ansible-option-title

      **fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone FQDN. The FQDN supplied at creation will be converted to canonical form.

      Read-only after creation.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/gss_tsig_enabled"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/gss_tsig_enabled:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/id:

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_assigned_hosts"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_assigned_hosts:

      .. rst-class:: ansible-option-title

      **inheritance_assigned_hosts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_assigned_hosts" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The list of the inheritance assigned hosts of the object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_assigned_hosts/display_name"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_assigned_hosts/display_name:

      .. rst-class:: ansible-option-title

      **display_name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_assigned_hosts/display_name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The human-readable display name for the host referred to by :emphasis:`ophid`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_assigned_hosts/host"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_assigned_hosts/host:

      .. rst-class:: ansible-option-title

      **host**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_assigned_hosts/host" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_assigned_hosts/ophid"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_assigned_hosts/ophid:

      .. rst-class:: ansible-option-title

      **ophid**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/inheritance_assigned_hosts/ophid" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The on-prem host ID.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources:

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/gss_tsig_enabled"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/gss_tsig_enabled:

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

      Optional. Field config for :emphasis:`gss\_tsig\_enabled` field from :emphasis:`AuthZone` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/gss_tsig_enabled/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/gss_tsig_enabled/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/gss_tsig_enabled/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/gss_tsig_enabled/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/gss_tsig_enabled/value:

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/notify"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/notify:

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

      Field config for :emphasis:`notify` field from :emphasis:`AuthZone` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/notify/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/notify/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/notify/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/notify/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/notify/value:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl:

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

      Optional. Field config for :emphasis:`query\_acl` field from :emphasis:`AuthZone` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/query_acl/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/value:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/value/access:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/value/acl:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/value/address:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/value/element:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key/algorithm:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key/comment:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key/key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key/name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key/protocol_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/query_acl/value/tsig_key/secret:

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
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl:

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

      Optional. Field config for :emphasis:`transfer\_acl` field from :emphasis:`AuthZone` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/transfer_acl/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/value:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/value/access:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/value/acl:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/value/address:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/value/element:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key/algorithm:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key/comment:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key/key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key/name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key/protocol_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/transfer_acl/value/tsig_key/secret:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl:

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

      Optional. Field config for :emphasis:`update\_acl` field from :emphasis:`AuthZone` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/update_acl/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/value:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/value/access:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/value/acl:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/value/address:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/value/element:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key/algorithm:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key/comment:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key/key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key/name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key/protocol_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/update_acl/value/tsig_key/secret:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/use_forwarders_for_subzones:

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

      Optional. Field config for :emphasis:`use\_forwarders\_for\_subzones` field from :emphasis:`AuthZone` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/use_forwarders_for_subzones/action"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/use_forwarders_for_subzones/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/use_forwarders_for_subzones/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/use_forwarders_for_subzones/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/use_forwarders_for_subzones/value:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority:

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

      Optional. Field config for :emphasis:`zone\_authority` field from :emphasis:`AuthZone` object.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/inheritance_sources/zone_authority/default_ttl"></div>

      .. raw:: latex

        \hspace{0.06\textwidth}\begin{minipage}[t]{0.26\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/default_ttl:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/default_ttl/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/default_ttl/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/default_ttl/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/default_ttl/value:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/expire:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/expire/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/expire/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/expire/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/expire/value:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/mname_block:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/mname_block/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/mname_block/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/mname_block/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/mname_block/value:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/mname_block/value/mname:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/mname_block/value/protocol_mname:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/mname_block/value/use_default_mname:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/negative_ttl:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/negative_ttl/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/negative_ttl/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/negative_ttl/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/negative_ttl/value:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/protocol_rname:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/protocol_rname/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/protocol_rname/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/protocol_rname/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/protocol_rname/value:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/refresh:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/refresh/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/refresh/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/refresh/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/refresh/value:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/retry:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/retry/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/retry/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/retry/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/retry/value:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/rname:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/rname/action:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/rname/display_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/rname/source:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/inheritance_sources/zone_authority/rname/value:

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
        <div class="ansibleOptionAnchor" id="return-objects/initial_soa_serial"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/initial_soa_serial:

      .. rst-class:: ansible-option-title

      **initial_soa_serial**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/initial_soa_serial" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`integer`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      On-create-only. SOA serial is allowed to be set when the authoritative zone is created.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/internal_secondaries"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/internal_secondaries:

      .. rst-class:: ansible-option-title

      **internal_secondaries**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/internal_secondaries" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Optional. BloxOne DDI hosts acting as internal secondaries. Order is not significant.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/internal_secondaries/host"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/internal_secondaries/host:

      .. rst-class:: ansible-option-title

      **host**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/internal_secondaries/host" title="Permalink to this return value"></a>

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

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/mapped_subnet"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/mapped_subnet:

      .. rst-class:: ansible-option-title

      **mapped_subnet**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/mapped_subnet" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Reverse zone network address in the following format: &quot;ip-address/cidr&quot;. Defaults to empty.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/mapping"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/mapping:

      .. rst-class:: ansible-option-title

      **mapping**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/mapping" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone mapping type. Allowed values:

      \* :emphasis:`forward`\ ,

      \* :emphasis:`ipv4\_reverse`.

      \* :emphasis:`ipv6\_reverse`.

      Defaults to forward.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/notify"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/notify:

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

      Also notify all external secondary DNS servers if enabled.

      Defaults to :emphasis:`false`.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/nsgs"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/nsgs:

      .. rst-class:: ansible-option-title

      **nsgs**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/nsgs" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/parent"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/parent:

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
        <div class="ansibleOptionAnchor" id="return-objects/primary_type"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/primary_type:

      .. rst-class:: ansible-option-title

      **primary_type**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/primary_type" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Primary type for an authoritative zone. Read only after creation. Allowed values:

      \* :emphasis:`external`\ : zone data owned by an external nameserver,

      \* :emphasis:`cloud`\ : zone data is owned by a BloxOne DDI host.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/protocol_fqdn"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/protocol_fqdn:

      .. rst-class:: ansible-option-title

      **protocol_fqdn**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/protocol_fqdn" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Zone FQDN in punycode.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/query_acl"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/query_acl:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/query_acl/access:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/query_acl/acl:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/query_acl/address:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/query_acl/element:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/query_acl/tsig_key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/query_acl/tsig_key/algorithm:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/query_acl/tsig_key/comment:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/query_acl/tsig_key/key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/query_acl/tsig_key/name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/query_acl/tsig_key/protocol_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/query_acl/tsig_key/secret:

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
        <div class="ansibleOptionAnchor" id="return-objects/tags"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/tags:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/transfer_acl:

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


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/transfer_acl/access"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/transfer_acl/access:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/transfer_acl/acl:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/transfer_acl/address:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/transfer_acl/element:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/transfer_acl/tsig_key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/transfer_acl/tsig_key/algorithm:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/transfer_acl/tsig_key/comment:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/transfer_acl/tsig_key/key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/transfer_acl/tsig_key/name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/transfer_acl/tsig_key/protocol_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/transfer_acl/tsig_key/secret:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/update_acl:

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

      Optional. Specifies which hosts are allowed to submit Dynamic DNS updates for authoritative zones of :emphasis:`primary\_type` :emphasis:`cloud`.

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/update_acl/access:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/update_acl/acl:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/update_acl/address:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/update_acl/element:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/update_acl/tsig_key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/update_acl/tsig_key/algorithm:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/update_acl/tsig_key/comment:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/update_acl/tsig_key/key:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/update_acl/tsig_key/name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/update_acl/tsig_key/protocol_name:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/update_acl/tsig_key/secret:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/updated_at:

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
        <div class="ansibleOptionAnchor" id="return-objects/use_forwarders_for_subzones"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/use_forwarders_for_subzones:

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
        <div class="ansibleOptionAnchor" id="return-objects/view"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/view:

      .. rst-class:: ansible-option-title

      **view**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/view" title="Permalink to this return value"></a>

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
        <div class="ansibleOptionAnchor" id="return-objects/warnings"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/warnings:

      .. rst-class:: ansible-option-title

      **warnings**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/warnings" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`list` / :ansible-option-elements:`elements=dictionary`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      The list of an auth zone warnings.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/warnings/message"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/warnings/message:

      .. rst-class:: ansible-option-title

      **message**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/warnings/message" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Warning message.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>


  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/warnings/name"></div>

      .. raw:: latex

        \hspace{0.04\textwidth}\begin{minipage}[t]{0.28\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/warnings/name:

      .. rst-class:: ansible-option-title

      **name**

      .. raw:: html

        <a class="ansibleOptionLink" href="#return-objects/warnings/name" title="Permalink to this return value"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`

      .. raw:: html

        </div>

      .. raw:: latex

        \end{minipage}

    - .. raw:: html

        <div class="ansible-option-indent-desc"></div><div class="ansible-option-indent-desc"></div><div class="ansible-option-cell">

      Name of a warning.


      .. rst-class:: ansible-option-line

      :ansible-option-returned-bold:`Returned:` Always


      .. raw:: html

        </div>



  * - .. raw:: html

        <div class="ansible-option-indent"></div><div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="return-objects/zone_authority"></div>

      .. raw:: latex

        \hspace{0.02\textwidth}\begin{minipage}[t]{0.3\textwidth}

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/zone_authority:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/zone_authority/default_ttl:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/zone_authority/expire:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/zone_authority/mname:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/zone_authority/negative_ttl:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/zone_authority/protocol_mname:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/zone_authority/protocol_rname:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/zone_authority/refresh:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/zone_authority/retry:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/zone_authority/rname:

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

      .. _ansible_collections.infoblox.bloxone.dns_auth_zone_info_module__return-objects/zone_authority/use_default_mname:

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
