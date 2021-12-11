# Deployer

## Methods

### ammParameters

```solidity
function ammParameters() external view returns (address factory, address underlyingToken, bytes32 rateOracleId, uint256 termStartTimestamp, uint256 termEndTimestamp)
```

Get the parameters to be used in constructing the pool, set transiently during pool creation.

_Called by the pool constructor to fetch the parameters of the pool Returns factory The factory address Returns underlyingToken Address of the underlying token Returns underlyingPool Address of the underlying pool Returns termEndTimestamp number of days from inception of the pool till maturity Returns termStartTimestamp Datetime of pool&#39;s inception_

#### Returns

| Name               | Type    | Description |
| ------------------ | ------- | ----------- |
| factory            | address | undefined   |
| underlyingToken    | address | undefined   |
| rateOracleId       | bytes32 | undefined   |
| termStartTimestamp | uint256 | undefined   |
| termEndTimestamp   | uint256 | undefined   |

### marginEngineParameters

```solidity
function marginEngineParameters() external view returns (address ammAddress)
```

#### Returns

| Name       | Type    | Description |
| ---------- | ------- | ----------- |
| ammAddress | address | undefined   |

### vammParameters

```solidity
function vammParameters() external view returns (address ammAddress)
```

#### Returns

| Name       | Type    | Description |
| ---------- | ------- | ----------- |
| ammAddress | address | undefined   |