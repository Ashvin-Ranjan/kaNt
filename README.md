# kaNt
An attempt at making a Minecraft server in N

This is mostly a clone of PrismaneJS's [flying squid](https://github.com/PrismarineJS/flying-squid)

Todo:
- [x] config
	- [x] `default-settings.n`
- [ ] docs
- [ ] examples
	- [ ] `basic.n`
- [x] logs
	- [x] `.gitignore`
- [ ] src
	- [x] plugins
	- [ ] lib
		- [ ] plugins
			- [ ] `animations.n`
			- [ ] `behavior.n`
			- [ ] `blockUpdates.n`
			- [ ] `blocks.n`
			- [ ] `channels.n`
			- [ ] `chat.n`
			- [ ] `chest.n`
			- [ ] `commands.n`
			- [ ] `communication.n`
			- [ ] `daycycle.n`
			- [ ] `digging.n`
			- [ ] `effects.n`
			- [ ] `entities.n`
			- [ ] `experience.n`
			- [ ] `external.n`
			- [ ] `header.n`
			- [ ] `health.n`
			- [ ] `inventory.n`
			- [ ] `log.n`
			- [ ] `login.n`
			- [ ] `logout.n`
			- [ ] `moderation.n`
			- [ ] `particle.n`
			- [ ] `physics.n`
			- [ ] `placeBlock.n`
			- [ ] `players.n`
			- [ ] `portal.n`
			- [ ] `pvp.n`
			- [ ] `redstone.n`
			- [ ] `respawn.n`
			- [ ] `settings.n`
			- [ ] `signs.n`
			- [ ] `sound.n`
			- [ ] `spawn.n`
			- [ ] `stats.n`
			- [ ] `tabComplete.n`
			- [ ] `tick.n`
			- [ ] `tp.n`
			- [ ] `updatePositions.n`
			- [ ] `useItem.n`
			- [ ] `weather.n`
			- [ ] `world.n`
		- [ ] worldGenerations
			- [ ] `all_the_blocks.n`
			- [ ] `grass_field.n`
			- [ ] `nether.n`
			- [ ] `superflat.n`
		- [ ] `behavior.n`
		- [ ] `command.n`
		- [x] `convertInventorySlotId.n`
		- [ ] `experience.n`
		- [x] `features.json`
		- [ ] `generations.n`
		- [ ] `playerDat.n`
		- [ ] `portal_detector.n`
		- [ ] `requireindex.n`
		- [ ] `supportFeature.n`
		- [ ] `user_error.n`
		- [x] `version.n`
	- [ ] `index.n`
- [ ] test
	- [ ] common
		- [ ] `parallel.n`
	- [ ] `mineflayer.test.n`
	- [ ] `portal.test.n`
	- [ ] `simple.test.n`
- [ ] tools
	- [ ] `dumpCodec.n`
- [ ] `app.n`
- [ ][kaNt-nbt](https://github.com/PrismarineJS/prismarine-nbt)
	- [ ] bench
		- [ ] `complied_nbt.n`
	- [ ] sample
		- [ ] `bigtest.n`
		- [ ] `bigtest.nbt` (Just Copy)
		- [ ] `bigtest.nbt.gz` (Just Copy)
		- [ ] `biome_definitions.le.nbt` (Just Copy)
		- [ ] `block_states.lev.nbt` (Just Copy)
		- [ ] `emptyComp.nbt` (Just Copy)
		- [ ] `level.dat` (Just Copy)
		- [ ] `readmeExample.n`
		- [ ] `sample.n`
		- [ ] `sampleLE.n`
	- [ ] test
		- [ ] `datatypes.n`
		- [ ] `nbt-cross-encode.n`
		- [ ] `nbt-spec.n`
	- [ ] typings
		- [ ] `index.d.n`
	- [ ] `compiler-compound.n`
	- [ ] `compiler-tagname.n`
	- [ ] `compiler-zigzag.n`
	- [ ] `compound.n`
	- [ ] `nbt-varint.n`
	- [ ] `nbt.n`
	- [ ] `nbt.json` (Just Copy)
- [ ][kaNt-chunk](https://github.com/PrismarineJS/prismarine-chunk)
	- [ ] src
		- [ ] pc
			- [ ] 1.13
				- [ ] `ChunkColumn.n`
				- [ ] `ChunkColumn.test.n`
				- [ ] `ChunkSection.n`
				- [ ] `ChunkSection.test.n`
				- [ ] `chunk.n`
			- [ ] 1.14
				- [ ] `ChunkColumn.n`
				- [ ] `ChunkSection.n`
				- [ ] `chunk.n`
			- [ ] 1.15
				- [ ] `ChunkColumn.n`
				- [ ] `ChunkSection.n`
				- [ ] `chunk.n`
			- [ ] 1.16
				- [ ] `ChunkColumn.n`
				- [ ] `ChunkSection.n`
				- [ ] `chunk.n`
			- [ ] 1.8
				- [ ] `section.n`
				- [ ] `chunk.n`
			- [ ] 1.9
				- [ ] `ChunkColumn.n`
				- [ ] `ChunkSection.n`
				- [ ] `chunk.n`
			- [ ] common
				- [ ] `BitArray.n`
				- [ ] `BitArray.test.n`
				- [ ] `BitArrayNoSpan.n`
				- [ ] `constants.n`
				- [ ] `neededBits.n`
				- [ ] `neededBits.test.n`
				- [ ] `varInt.n`
				- [ ] `varInt.test.n`
		- [ ] pe
			- [ ] 0.14
				- [ ] `chunk.n`
			- [ ] 1.0
				- [ ] `chunk.n`
				- [ ] `subchunk.n`
		- [ ] `index.n`
	- [ ] test
		- [ ] `test.n`
		- [ ] Everything else (Just Copy)
	- [ ] types
		- [ ] `index.d.n`
		- [ ] `chunk.d.n`
		- [ ] `section.d.n`
	- [ ] `index.n`
	- [ ] `example.n`