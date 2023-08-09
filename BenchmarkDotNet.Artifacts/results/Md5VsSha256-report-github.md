``` ini

BenchmarkDotNet=v0.13.2, OS=Windows 10 (10.0.19044.3086/21H2/November2021Update)
Intel Core i9-8950HK CPU 2.90GHz (Coffee Lake), 1 CPU, 12 logical and 6 physical cores
.NET SDK=7.0.201
  [Host]     : .NET 6.0.14 (6.0.1423.7309), X64 RyuJIT AVX2
  DefaultJob : .NET 6.0.14 (6.0.1423.7309), X64 RyuJIT AVX2


```
| Method |     Mean |    Error |   StdDev |
|------- |---------:|---------:|---------:|
| Sha256 | 766.7 ns | 12.92 ns | 11.45 ns |
|    Md5 | 411.7 ns |  8.15 ns | 12.44 ns |
