# Hi, I'm Nikita 👋

### C++ Developer interested in high-performance systems

I am a Computer Science and Applied Mathematics student at Moscow Aviation Institute. I'm interested in how high-performance software works under the hood, particularly database internals, concurrency, asynchronous programming, and efficient resource management.

My main language is modern **C++ (17/20/23)**. I enjoy exploring multithreading, synchronization, coroutines, and Linux internals, as well as studying the architecture of systems such as ClickHouse, DuckDB, and userver.

I also enjoy working with algorithms, data structures, and low-level data processing. Through personal projects, I explore topics such as compression algorithms, indexing, inter-process communication, and modern C++ design. Alongside development, I sharpen my problem-solving skills through competitive programming.

## What I work with

- **Languages:** C++, Rust, C, Python, SQL, Bash
- **C++ ecosystem:** STL, templates, Boost, CMake, userver
- **Concurrency & systems:** multithreading, asynchronous programming, synchronization, POSIX, IPC, memory management, Linux
- **Algorithms & data:** data compression, indexing, information retrieval, algorithms and data structures
- **Backend:** FastAPI, Django, NumPy, pandas
- **Tools:** Git, GitHub, GitLab, Docker, CI, code review
- **Foundations:** operating systems, software architecture, OOP, linear algebra

## Featured projects

### [BWT Compressor](https://github.com/pozercpp/bwt_compressor)

A C++23 lossless file compressor with a reusable compression library and a command-line interface. It implements a block-based compression pipeline combining the **Burrows–Wheeler Transform (BWT), Move-to-Front (MTF), Run-Length Encoding (RLE), and entropy coding**.

The compressor supports adaptive arithmetic coding and canonical Huffman coding, automatically selecting the smaller encoded representation or storing raw data when compression is ineffective.

Key features include:

- Block-based compression and decompression with blocks up to 1 MiB.
- Custom binary formats (`BWC1` and `BWA1`) with CRC-32 integrity checks.
- Support for arbitrary binary data and input validation during decompression.
- A reusable C++ library with a `std::span`-based API, CLI tools, and automated tests.

`C++23` `CMake` `BWT` `MTF` `RLE` `Arithmetic Coding` `Huffman Coding` `CRC-32`

### [Full-Text Search Engine](https://github.com/pozercpp/search_engine)

A C++20 search engine for local document collections with recursive indexing, boolean queries, BM25 ranking, JSON index persistence, and an interactive CLI.

The project uses an in-memory inverted index with term frequencies and positions, supports AND/OR query processing, and follows a layered architecture with separate tokenization, indexing, ranking, query, and utility components.

`C++20` `CMake` `STL` `nlohmann/json` `Inverted Index` `BM25`

### [POSIX FIFO Messenger](https://github.com/pozercpp/MESSENGER)

A C++20 client-server messaging system built around POSIX named pipes (FIFO), exploring inter-process communication, multithreading, and synchronization on Linux.

The system supports authentication, direct messages, delayed delivery, and store-and-forward messaging for offline users. It uses POSIX threads for asynchronous message delivery and mutexes to synchronize shared server state.

`C++20` `POSIX FIFO` `pthreads` `IPC` `Linux` `CMake`

## Highlights

- Prize winner at **RuCode 2025**
- Graduate of **Yandex Backend Development School (C++ track), 2026**
- BSc in Computer Science and Applied Mathematics at **Moscow Aviation Institute**, 2024–2028

## GitHub language statistics

\<p align="center">   \<a href="[https://github.com/pozercpp](https://github.com/pozercpp)">     \<img       src="[https://github-readme-stats.vercel.app/api/top-langs/?username=pozercpp&layout=compact&langs_count=8&theme=transparent&hide_border=true&title_color=58a6ff&text_color=8b949e](https://github-readme-stats.vercel.app/api/top-langs/?username=pozercpp\&layout=compact\&langs_count=8\&theme=transparent\&hide_border=true\&title_color=58a6ff\&text_color=8b949e)"       alt="Nikita's most used languages"     />   \</a> \</p>

> The chart is generated from public GitHub repositories and does not represent my exact experience level in each language.
