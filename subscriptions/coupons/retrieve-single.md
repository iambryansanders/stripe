#### Retrieve a coupon

Retrieves the coupon with the given ID.

##### Arguments

<table>
    <tbody>
        <tr valign="top">
            <td width="20%" style="text-align: right">
                <small>string</small> <strong>$couponId</strong><br />
                <small style="color: teal;">REQUIRED</small>
            </td>
            <td width="80%">
                The coupon unique identifier.
            </td>
        </tr>
    </tbody>
</table>

##### Usage

```php
$coupon = $stripe->coupons()->find('50-PERCENT-OFF');

echo $coupon['percent_off'];
```