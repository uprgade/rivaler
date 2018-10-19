# Swagger\Client\ProductsApi

All URIs are relative to *https://price.localhost/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getProductsSearchUrl**](ProductsApi.md#getProductsSearchUrl) | **GET** /products/search-url | Search product by Url


# **getProductsSearchUrl**
> getProductsSearchUrl($url)

Search product by Url

Returns one product

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\ProductsApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$url = "url_example"; // string | Product url encoded

try {
    $apiInstance->getProductsSearchUrl($url);
} catch (Exception $e) {
    echo 'Exception when calling ProductsApi->getProductsSearchUrl: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **url** | **string**| Product url encoded |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

