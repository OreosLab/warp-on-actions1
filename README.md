# warp-on-actions

* * *

### Usage example:
client warp+doh mode
```
  - name: Set up WARP
    uses: fscarmen/warp-on-actions@latest
    with:
      mode: client  # Optional. Support [ client, wireguard ]. Default is client.
      stack: dual   # Optional. Support [ ipv4, ipv6, dual ]. Default is dual.
```

### Input Parameters

| Parameter | **Mandatory**/**Optional** | Description |
| --------- | -------- | ----------- |
| mode | **Optional** | Install WARP mode: `client` is warp+doh mode, `wireguard` is wireguard mode. Default is `client`. |
| stack | **Optional** | WARP stack: one of `ipv4`, `ipv6`,`dual`. Default is `dual`. |
