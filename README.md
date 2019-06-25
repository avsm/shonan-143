# Programming Language Support for Data-intensive Applications (Shonan 143)

This repository contains the organisational information about the [Shonan meeting
#143](https://shonan.nii.ac.jp/seminars/143/), held in Japan from July 1-5th 2019.  It will eventually also hold the
final report once the meeting has concluded.

- *Date*: July 1 - 5, 2019
- *Organisers*: Suresh Jaganathan, Oleg Kiselov, Anil Madhavapeddy, KC Sivaramakrishnan
- *Homepage*: https://shonan.nii.ac.jp/seminars/143/
- *Local Information*: https://github.com/avsm/shonan-143/wiki

## Abstract

The landscape of data-intensive applications today span the gamut from large-scale Web applications (expected to provide persistent, fault-tolerant, high-availability and low-latency geo-distributed services), to unreliably connected IoT networks comprised of millions of heterogeneous devices streaming and processing realtime data feeds. In both cases, application logic is usually expressed using high-level, often domain-specific, language abstractions, while data management issues are typically relegated to an opaque monolithic data querying and storage service. While this architecture encourages separation of concerns, it provides little opportunity for synergies between the application and database/storage boundary. In particular, applying well-understood programming language principles, compiler optimizations and verification techniques to ensure data management services enforce application-level invariants becomes difficult, jeopardizing safety and maintainability.

To overcome these drawbacks, we require a radically different view of how applications and datastores interact with one another. We propose to organize a Shonan meeting to bring together programming language experts and practitioners of cutting-edge data-intensive applications to discuss how we can unfiy data representation issues across different layers of the application stack to exploit the benefits of program verification and optimization to realize correctness and performance in the data processing layer. Central to our approach is the application of declarative abstractions and methodologies to express storage requirements without exposing low-level system-specific details.
