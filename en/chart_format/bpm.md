﻿# BPM

Introduction to BPM components in a chart.
::: info Tips
**All fields on this page have compatibility level 0.**
:::

## Json Example

```json
{
  "Bpm": 120.0,
  "StartBeat": 0.0
}
```

## Structural specifications

| Unique Identifier |   Field   | Type  | Description                                    | Default Value | Added Version |
|:-----------------:|:---------:|:-----:|:-----------------------------------------------|:-------------:|:-------------:|
|         1         |    Bpm    | float | BPM value for this segment, unit: BPM          |     120.0     |       1       |
|         2         | StartBeat | float | The beat position where this BPM takes effect  |      0.0      |       1       |