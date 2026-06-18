# SafeMark Chroma Firewall v1

Validates AI color streams in **847ns** — built after parser flaw research.

## Benchmark
`std::chrono::high_resolution_clock`, -O3, 1M iterações = 847ns por token

## Run
g++ -std=c++17 test_proof.cpp -o test_proof && ./test_proof

## Proof-of-contact
111101a@proton.me (null-name U+0000)
