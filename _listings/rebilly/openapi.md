swagger: "2.0"
x-collection-name: Rebilly
x-complete: 1
info:
  title: Rebilly
  description: -introductionthe-rebilly-api-is-built-on-http---our-api-is-restful---it-has-predictableresource-urls---it-returns-http-response-codes-to-indicate-errors---it-alsoaccepts-and-returns-json-in-the-http-body---you-can-use-your-favoritehttprest-library-for-your-programming-language-to-use-rebillys-api-oryou-can-use-one-of-our-sdks-currently-available-in-phphttpsgithub-comrebillyrebillyphpand-chttpsgithub-comrebillyrebillydotnetclient--authenticationwhen-you-sign-up-for-an-account-you-are-given-your-first-api-key-you-can-generate-additional-api-keys-and-delete-api-keys-as-you-mayneed-to-rotate-your-keys-in-the-future--you-authenticate-to-therebilly-api-by-providing-your-secret-key-in-the-request-header-rebilly-offers-three-forms-of-authentication--private-key-json-web-tokens-andpublic-key--private-key-authenticates-each-request-by-searching-for-the-presenceof-an-http-header-rebapikey--jwt-authenticates-each-request-by-the-http-header-authorization--public-key-authenticates-by-the-http-header-rebauth-read-more-on-this-below-rebilly-also-offers-json-web-tokens-jwt-authentication-where-you-can-controlthe-specific-granular-permissions-and-expiration-for-that-jwt---we-call-our-resourcefor-generating-jwt-sessionstagsessions-rebilly-also-has-a-clientside-authentication-scheme-that-uses-anapiuser-and-hmacsha1-signature-only-for-the-tokens-resource-sothat-you-may-safely-create-tokens-from-the-clientside-without-compromisingyour-secret-keys-never-share-your-secret-keys--keep-them-guarded-and-secure-the-clientside-authentication-scheme-uses-one-http-header-named-rebauth--redocinject-securitydefinitions--php-sdkfor-all-php-sdk-examples-provided-in-this-spec-you-will-need-to-configure-client-you-may-do-it-like-thisphpclient--new-rebillyclient----apikey--yourapikeyhere----baseurl--httpsapi-rebilly-com
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /coupons-redemptions/{id}:
    get:
      summary: Retrieve a coupon redemption with specified identifier string
      description: ""
      operationId: coupons_redemptions.id.get
      x-api-path-slug: couponsredemptionsid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Coupon
      - Redemption
      - Specified
      - Identifier
      - String
  /tracking/api/{id}:
    get:
      summary: Retrieve a tracking API log with specified identifier string
      description: ""
      operationId: ""
      x-api-path-slug: trackingapiid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Tracking
      - Log
      - Specified
      - Identifier
      - String
  /tracking/subscriptions/{id}:
    get:
      summary: Retrieve a tracking subscription log with specified identifier string
      description: ""
      operationId: ""
      x-api-path-slug: trackingsubscriptionsid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Tracking
      - Subscription
      - Log
      - Specified
      - Identifier
      - String
  /tracking/website-webhooks/{id}:
    get:
      summary: Retrieve a tracking webhook notification with specified identifier
        string
      description: ""
      operationId: ""
      x-api-path-slug: trackingwebsitewebhooksid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Tracking
      - Webhook
      - Notification
      - Specified
      - Identifier
      - String