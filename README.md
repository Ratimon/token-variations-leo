# token_variations_leo.aleo

## Build Guide

To compile this Aleo program, run:
```bash
snarkvm build
```

To execute this Aleo program, run:
```bash
snarkvm run hello
```

## Quick Guide

To initiate a new project

```bash
leo new token_variations_leo
```

To mint the token

```bash
leo run mint 100u32
```

To transfer the token

```bash
leo run transfer aleo19mh3ypqge6utk5jqypf5a3nz6mj63u44c2mtemjnja6kx5524u8suz44hp 10u32 "{
    owner: aleo19mh3ypqge6utk5jqypf5a3nz6mj63u44c2mtemjnja6kx5524u8suz44hp.private,
    balance: 10u32.private,
    _nonce: 3767145948821681062917749761220735365475344605508258106668424643030153899146group.public
}"
```