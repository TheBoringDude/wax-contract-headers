# wax-contract-headers

Useful headers for contract development in the WAX blockchain.

#### Note: These header files are taken from other projects.

## Headers

- `atomicassets.hpp`

  Used for accessing the `atomicassets` contract.

- `ram.hpp`

  For managing account / wallet ram.

- `wax-orng.hpp`

  WAX ORNG smart contract simple header.

## Utils

- `now()` - get the current utc / system time

```c++
uint32_t now() {
    return current_time_point().sec_since_epoch();
}
```
