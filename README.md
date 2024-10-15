https://docs.konghq.com/hub/kong-inc/rate-limiting/configuration/

TODO Show logs or metrics by limit_by (The entity that is used when aggregating the limits.)

# Headers

* RateLimit-Limit: Shows the maximum number of requests allowed in the specified time period.
* RateLimit-Remaining: Indicates the number of requests remaining within the current limit window.
* RateLimit-Reset: Specifies the time (in seconds) until the rate limit resets.

* X-RateLimit-Limit-Minute: Number of requests allowed per minute.
* X-RateLimit-Remaining-Minute: Remaining requests for the current minute.

* [Retry-After: 55](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Retry-After)

Additional headers:

* X-Kong-Upstream-Latency: 1178
* X-Kong-Proxy-Latency: 58
* Via: 1.1 kong/3.8.0
* X-Kong-Request-Id: 0af3be060e44b5360ccf63076c94866b
