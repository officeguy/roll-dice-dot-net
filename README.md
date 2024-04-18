# roll-dice-dot-net

This app is the dot net implemenation of the roll the dice sample app, from the OpenTelemetry repo.

.Net
https://opentelemetry.io/docs/languages/net/getting-started/

Other Language versions are also available if required:
- C++: https://opentelemetry.io/docs/languages/cpp/getting-started/
- Erlang/Elixir: https://opentelemetry.io/docs/languages/erlang/getting-started/
- Go: https://opentelemetry.io/docs/languages/go/getting-started/
- Java: https://opentelemetry.io/docs/languages/java/getting-started/
- Javascript/NodeJs: https://opentelemetry.io/docs/languages/js/getting-started/nodejs/
- PHP: https://opentelemetry.io/docs/languages/php/getting-started/
- Python: https://opentelemetry.io/docs/languages/python/getting-started/
- Ruby: https://opentelemetry.io/docs/languages/ruby/getting-started/
- Rust: https://opentelemetry.io/docs/languages/rust/getting-started/
- Swift: https://opentelemetry.io/docs/languages/swift/getting-started/


Related Otel Issue where the sample apps were proposed: https://github.com/open-telemetry/opentelemetry.io/issues/2623



## Features
The app provides an API endpoint which returns a random number between 1 and 6, i.e a dice roll

The endpoint is available at http://localhost:8080/rolldice

An html client is avilable in this folder /client/client.htm 

The app is instrumented using OpenTelemetry, which have exporters which write to the console. 

## Usage
- Clone the git repo using
```
git clone https://github.com/Kiwibank/roll-dice-dot-net
```

- On the command line, change into the directory and run:
```
dotnet run
```

## Future plans
  
