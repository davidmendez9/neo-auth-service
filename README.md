# Neo Auth Service

`neo-auth-service` is a Java library designed to facilitate JWT-based authentication. It provides essential tools for generating, verifying, and managing JSON Web Tokens (JWTs), as well as utilities for secure password handling.

## Installation

To use `neo-auth-service` in your project, add the following dependencies to your `build.gradle` file:

```gradle
dependencies {
    implementation 'org.neocoder:1.0'
}
```

## How to use

For detailed usage instructions and API documentation, please refer to the Java Docs.

### TokenService

The `TokenService` class provides methods for generating and verifying JWTs. To create a new `TokenService`, you need to provide a secret key, issuer, and token expiration time in seconds.

```java
    TokenService tkn = new TokenService("secretpass123", "myApplication", 3600);
```

## Running Tests

To run the test, open a terminal in the root of the service folder and execute the following command:

```bash
    ./gradlew test
```

## Running coverage

You need to have gradle on your project.


To run the coverage, open a terminal in the root of the service folder and execute the following command: 
```bash
    ./gradlew jacocoTestReport
```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue on GitHub.

## License

_neo-auth-service_ is distributed under the MIT License. See LICENSE for more information.