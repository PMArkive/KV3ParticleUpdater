# KeyValue3 Particle Updater for S&Box
Update old KeyValues3 particle features to new versions for S&Box.

> [!WARNING]
> KV3ParticleUpdater has not been updated since Sep 2022 and probably no longer works with modern sbox!

Made for TF:S2 so may not convert all particle features, but most should be covered.

Special thanks to [justyn0](https://github.com/justyn0) for his work on working out how to translate many particle features to the S&Box versions.

## Adding new Updaters
Check existing updaters to see how to make a new updater. Covered use cases are:

- Move block to new block (e.g. move to operators)
- Replace an old block with new data
- Insert some data into an existing block
- Update a block to "C_INIT_InitFloat"

Any new Updater type added is automatically used.

## Currently updated particle features:
- Age Noise (Remove)
- CreateAlongPath
- CreateSequentialPath
- CreationNoise
- *Custom overbright addition for some sprites*
- PositionWarp
- RandomAlpha
- RandomColor
- RandomLifeTime
- RandomRadius
- RandomRotaionSpeed
- RandomSecondSequence
- RandomSequence
- RandomTrailLength
- RandomYawFlip
- RandomYaw
- RemapCpToVector
- RemapScalar
