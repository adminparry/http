# http状态码

https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Status

``` dart
abstract class HttpStatus {
  static const int continue_ = 100;
  static const int switchingProtocols = 101;
  @Since("2.1")
  static const int processing = 102;
  static const int ok = 200;
  static const int created = 201;
  static const int accepted = 202;
  static const int nonAuthoritativeInformation = 203;
  static const int noContent = 204;
  static const int resetContent = 205;
  static const int partialContent = 206;
  @Since("2.1")
  static const int multiStatus = 207;
  @Since("2.1")
  static const int alreadyReported = 208;
  @Since("2.1")
  static const int imUsed = 226;
  static const int multipleChoices = 300;
  static const int movedPermanently = 301;
  static const int found = 302;
  static const int movedTemporarily = 302; // Common alias for found.
  static const int seeOther = 303;
  static const int notModified = 304;
  static const int useProxy = 305;
  static const int temporaryRedirect = 307;
  @Since("2.1")
  static const int permanentRedirect = 308;
  static const int badRequest = 400;
  static const int unauthorized = 401;
  static const int paymentRequired = 402;
  static const int forbidden = 403;
  static const int notFound = 404;
  static const int methodNotAllowed = 405;
  static const int notAcceptable = 406;
  static const int proxyAuthenticationRequired = 407;
  static const int requestTimeout = 408;
  static const int conflict = 409;
  static const int gone = 410;
  static const int lengthRequired = 411;
  static const int preconditionFailed = 412;
  static const int requestEntityTooLarge = 413;
  static const int requestUriTooLong = 414;
  static const int unsupportedMediaType = 415;
  static const int requestedRangeNotSatisfiable = 416;
  static const int expectationFailed = 417;
  @Since("2.1")
  static const int misdirectedRequest = 421;
  @Since("2.1")
  static const int unprocessableEntity = 422;
  @Since("2.1")
  static const int locked = 423;
  @Since("2.1")
  static const int failedDependency = 424;
  static const int upgradeRequired = 426;
  @Since("2.1")
  static const int preconditionRequired = 428;
  @Since("2.1")
  static const int tooManyRequests = 429;
  @Since("2.1")
  static const int requestHeaderFieldsTooLarge = 431;
  @Since("2.1")
  static const int connectionClosedWithoutResponse = 444;
  @Since("2.1")
  static const int unavailableForLegalReasons = 451;
  @Since("2.1")
  static const int clientClosedRequest = 499;
  static const int internalServerError = 500;
  static const int notImplemented = 501;
  static const int badGateway = 502;
  static const int serviceUnavailable = 503;
  static const int gatewayTimeout = 504;
  static const int httpVersionNotSupported = 505;
  @Since("2.1")
  static const int variantAlsoNegotiates = 506;
  @Since("2.1")
  static const int insufficientStorage = 507;
  @Since("2.1")
  static const int loopDetected = 508;
  @Since("2.1")
  static const int notExtended = 510;
  @Since("2.1")
  static const int networkAuthenticationRequired = 511;
  // Client generated status code.
  static const int networkConnectTimeoutError = 599;
}

```