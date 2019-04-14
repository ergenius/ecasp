# ecasp
Cassandra CQL binary protocol parser and serializer

[![Build Status](https://api.travis-ci.org/ergenius/epool.svg?branch=master)](https://travis-ci.org/ergenius/ecasp)

Ecasp is a library for Erlang implementing a full Cassandra CQL binary protocol parser and serializer. 
Ecasp covers all CQL v.3, v.4 and v.5 specifications.
Ecasp is **insanely documented** with a focus on **performance**, **extensibility** and **functionality**.
Ecasp can be used to create new Cassandra erlang drivers easier, helping developers to start faster and focus more on the performance aspects of their driver than on the hasle of rewriting another erlang CQL protocol parser from scratch.

## Projects using ecasp

- ecas - Erlang Driver for Apache Cassandra - https://github.com/ergenius/ecas

## Projects ecasp was hardly inspired by

- cqerl - Native Erlang CQL client for Cassandra - https://github.com/matehat/cqerl

## Project roadmap

1. Continuously fix bugs and tune performance.
2. Implement any new CQL protocol version Cassandra development team will come up with.
3. Write more testing units.

## Erlang versions supported

Ecasp officially supports OTP release 17 and later.

Development of Ecasp takes place using a OTP 21.0 release and tests are done on:
- 17.5
- 18.3
- 19.3
- 20.0
- 21.0

Unofficially you may be able to use Ecasp with older Erlang versions. No guarantee included.

## Dependencies

I didn't like to have any project dependencies that can easily introduce versioning conflicts in bigger applications that use the same dependencies. Ecasp uses only standard OTP, no other application is needed and will ever be.

## Authors

- Madalin Grigore-Enescu (ergenius) <os@ergenius.com>

## License

Ecasp is available in the public domain.

Ecasp is also optionally available under the MIT license (see `LICENSE`) for jurisdictions that do not recognize public domain works.
