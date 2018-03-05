#### Retrieve a SKU

Retrieves the details of an existing SKU. Supply the unique SKU identifier from either a SKU creation request or from the product, and Stripe will return the corresponding SKU information.

##### Arguments

<table>
    <tbody>
        <tr valign="top">
            <td width="20%" style="text-align: right">
                <small>string</small> <strong>$skuId</strong><br />
                <small style="color: teal;">REQUIRED</small>
            </td>
            <td width="80%">
                The SKU unique identifier.
            </td>
        </tr>
    </tbody>
</table>

##### Usage

```php
$sku = $stripe->skus()->find('sku_Bnf8QnZxQ2UVtx');

echo $sku['name'];
```