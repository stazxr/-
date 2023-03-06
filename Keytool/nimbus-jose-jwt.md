nimbus-jose-jwt是基于Apache2.0开源协议的JWT开源库，支持所有的签名(JWS)和加密(JWE)算法。

JWT是一种规范，它强调了两个组织之间传递安全的信息
JWS是JWT的一种实现，包含三部分header(头部）、payload(载荷）、signature(签名）
JWE也是JWT的一种实现，包含五部分内容

依赖：
<dependency>
    <groupId>com.nimbusds</groupId>
    <artifactId>nimbus-jose-jwt</artifactId>
    <version>8.16<version>
</dependency>
