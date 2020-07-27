# BigInteger.NetCore
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![nuget](https://img.shields.io/nuget/v/BigInteger.NetCore.svg)](https://www.nuget.org/packages/BigInteger.NetCore/)

Implementation of a arbitrary-precision arithmetic method using [SecureRandom](https://github.com/TimothyMeadows/SecureRandom.NetCore).

# Install

From a command prompt
```bash
dotnet add package BigInteger.NetCore
```

```bash
Install-Package BigInteger.NetCore
```

You can also search for the package via your nuget ui / website:

https://www.nuget.org/packages/BigInteger.NetCore/

# Examples

You can find more examples in the github examples project.

```csharp
var b1 = new BigInteger(long.MaxValue.ToString());
var b2 = new BigInteger(long.MaxValue.ToString());
var b3 = b1.Add(b2);
var p3 = b3.Pow(3);
```
