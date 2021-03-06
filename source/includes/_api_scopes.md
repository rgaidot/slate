## <span class="jumptarget"> <a name="scopes"></a> OAuth Scopes </span>

The following table identifies the name used for each OAuth scope in the My Apps and control panel GUIs, along with the corresponding resources and the strings that get passed to your app during apps' [installation or scope updates](/api/v2/#installation).

All OAuth scopes except `default` have `read_only` scopes that allow only `GET` and `HEAD` requests.

<aside class="warning">
MIGRATION NOTE: All links in the right column need to be re-set!
</aside>

| Scope GUI Name | Scope Strings | Resources |
| --- | --- | --- |
| Content | **store_v2_content** |[blog/posts](/api/stores/v2/blog/posts)|
||**store_v2_content_read_only** |[blog/tags](/api/stores/v2/blog/tags)|
|||[redirects](/api/stores/v2/redirects)|
| Customers | **store_v2_customers**|[customers](/api/stores/v2/customers)|
||**store_v2_customers_read_only** | [customers/{id}/addresses](/api/stores/v2/customers/addresses)|
|||[customer_groups](/api/stores/v2/customer_groups) |
| Default | **default** | [countries](/api/stores/v2/countries)|
|||[countries/{id}/states](/api/stores/v2/countries/states)|
|||[hooks](/api/stores/v2/webhooks)
|||[time](/api/stores/v2/time) |
| Information | **store_v2_information**|[payments/methods](/api/stores/v2/payments/methods)
||**store_v2_information_read_only** | [shipping/methods](/api/stores/v2/shipping/methods)
|||[store](/api/stores/v2/store_information)
|||[tax_classes](/api/stores/v2/tax_classes) |
| Marketing | **store_v2_marketing**|[coupons](/api/stores/v2/coupons) |
||**store_v2_marketing_read_only** | |
| | | [gift_certificates](/api/stores/v2/gift_certificates)|
| Orders | **store_v2_orders**| [orders](/api/stores/v2/orders) |
||**store_v2_orders_read_only** | [orders/{id}/coupons](/api/stores/v2/orders/coupons)|
|||[orders/{id}/messages](/api/stores/v2/orders/messages) |
|||[orders/{id}/products](/api/stores/v2/orders/products) |
|||[orders/{id}/shipping_addresses](/api/stores/v2/orders/shipping_addresses) |
|||[orders/{id}/order_statuses](/api/stores/v2/order_statuses) |
|||[orders/{id}/taxes](/api/stores/v2/orders/taxes) |
|||[orders/{id}/shipments](/api/stores/v2/orders/shipments) |
| Products | **store_v2_products**|[brands](/api/stores/v2/brands) |
||**store_v2_products_read_only** | [products/{id}/discount_rules](/api/stores/v2/products/discount_rules) |
|||[categories](/api/stores/v2/categories) |
|||[products/{id}/configurable_fields](/api/stores/v2/products/configurable_fields) |
|||[products/{id}/custom_fields](/api/stores/v2/products/custom_fields) |
|||[products/{id}/googleproductsearch](/api/stores/v2/products/googleproductsearch) |
|||[options](/api/v2/products/#product-options) |
|||[option_sets](/api/v2/products/#option-sets) |
|||[option_sets/{id}/options](/api/v2/products/#option-sets-options) |
|||[options/{id}/values](/api/v2/products/#product-option-values) |
|||[products](/api/v2/products) |
|||[products/{id}/images](/api/v2/products/#product-images) |
|||[products/{id}/options](/api/v2/products/#product-options) |
|||[products/{id}/reviews](/api/v2/products/#product-reviews) |
|||[products/{id}/rules](/api/v2/products/#product-rules) |
|||[products/{id}/videos](/api/v2/products/#products-videos) |
|||[products/{id}/skus](/api/v2/products/#product-skus) |
