# turtle-fasthash
testnet, disregard.

```
// CN_Turtle2x Definitions
#define MEMORY_Light           2097152 // 2MB  scratchpad 2^21
#define ITER_Light             262144  // 2^18 1st round
#define ITER_Light_Divided     131072  // 2^17 2nd round
#define CN_LIGHT_INIT          (MEMORY_Light / INIT_SIZE_BYTE)
#define CN_LIGHT_AES_INIT      (MEMORY_Light / AES_BLOCK_SIZE)

// CN_Turtle4x Definitions
#define MEMORY_Light           4194304 // 4MB scratchpad 2^22
#define ITER_Light             262144  // 2^17 1st Round
#define ITER_Light_Divided     131072  // 2^16 2nd Round
#define CN_LIGHT_INIT          (MEMORY_Light / INIT_SIZE_BYTE)
#define CN_LIGHT_AES_INIT      (MEMORY_Light / AES_BLOCK_SIZE)
```
