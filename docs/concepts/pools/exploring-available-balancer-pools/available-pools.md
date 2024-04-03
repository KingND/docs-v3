---
order: 1
title: Available Balancer Pools
---

## Pool Types

Let's explore some of the diverse pool types within the Balancer Protocol, each tailored to specific use cases.

- [Weighted Pools](./weighted-pool.md): Weighted Pools are highly versatile and configurable pools. They are ideal for general cases and enable users to build pools with different token counts and weightings.
- [Stable Pools](./stable-pool.md): Stable Pools are optimal for assets expected to consistently trade at near parity or with a known exchange rate.
- [Boosted Pool](./boosted-pool.md): Boosted Pools are designed to allow for greater capital efficiency, deeper liquidity, and increased yield for Liquidity Providers.
- [80/20 Pool](./80-20-pool.md): An optimised version of the Weighted Pool with set weights of 80%/20%. The perfect fit for achieving liquidity of governance tokens.
- [Liquidity Bootstrapping pools](./liquidity-bootstrapping-pool.md): Liquidity Bootstrapping Pools (LBPs) are pools that can dynamically change token weighting. LBPs create sell pressure and fair market advantages. Used very succesfully for fair token launches.

Every pool type is associated with its own Factory contract, facilitating the creation of new pools. Experienced developers can find the factory deployment addresses through [this resource](../../../reference/contracts/deployment-addresses/mainnet.md) and refer to [this guide](../../developer-guides/weighted-pool-creation-example.md) for more detailed instructions. For further assistance, individuals are encouraged to contact our developers via [Discord](https://discord.balancer.fi/).


