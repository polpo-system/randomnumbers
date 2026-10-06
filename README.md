# RandomNumbers of ETH Oberon, for polpo

`RandomNumbers`: `Uniform()` (in [0, 1)), `Exp(mu)` (exponentially distributed, mean 1/mu)
and `InitSeed(seed)`; the seed starts from the clock (`Oberon.GetClock`, so the module uses
the desktop). It needs `Math` (the package math).

From ETH Oberon (OLR), converted to plain text. `test/RNTest.Mod`: `RNTest.Run` checks the
range and the means; it needs the desktop (DISPLAY).

Install with portia: `portia.Install randomnumbers`. The license is the one of ETH Oberon: `LICENSE`.
