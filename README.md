https://www.nsnam.org/docs/release/3.46/tutorial/html/
https://www.nsnam.org/releases/latest

### Basic Concepts

- `Node`: computing device that connects to a network (like a host or endpoint)
- `Application`: a user program that generates some activity to be simulated
- `Channel`: provides methods for managing communication subnetwork objects and connecting nodes to them
- `NetDevice`: provides methods for managing connections to `Node` and `Channel` objects

### Running Simulations

```shell
./ns3 configure -d debug --enable-examples --enable-tests
./ns3 build
```

---

### Personal Note

- [ ] 이부분 compsys 수업에서 했던 프로젝트랑 연결해서 정리해보기