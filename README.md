# Rust gRPC demo

Minimal example of a RPC server written in Rust.

```bash
# System deps (for MacOS)
brew install protobuf
brew install grpc

# Require Rust installed
cargo run

# In another term, call the RPC server
grpc_cli call localhost:50052 bookstore.Bookstore.GetBook "id: 'test-book-id'"
```
