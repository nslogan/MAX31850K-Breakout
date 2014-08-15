# MAX31850K-Breakout

## Description

A small breakout board for the Maxim MAX31850K 1-wire type-K thermocouple amplifier with CJC. Project [available on GitHub](https://github.com/nslogan/MAX31850K-Breakout").

## Production

The board measures 0.85x0.85in (21.62x21.62mm) and is designed for production at [OSH Park](https://www.oshpark.com/). The OSHPark DRU is located in the `res/` folder.

The boards can be purchased [here](https://oshpark.com/shared_projects/TtoEusV0) @ $3.60 for three.

## Parts

All parts on this board are from the [LoganSmith-Eagle-Library](https://github.com/nslogan/LoganSmith-Eagle-Library) available on GitHub (work in progress).

The BOM is located in the `release/` folder, all parts are sourced from Digi-Key.

## Project Structure

This project adheres to this structure:

	[ProjectName]
		README.md
		[release]
			[Major.Minor]
				ProjectName_BOM_Major.Minor.xls or ProjectName_BOM_BOM_Major.Minor.csv
				ProjectName_schematic_Major.Minor.pdf
				ProjectName_board-<top/mid#/bottom>_Major.Minor.png
				ProjectName_Major.Minor.sch
				ProjectName_Major.Minor.brd
				[Gerbers]
					...
			...
		[src]
			[Major.0]
				BoardName.sch
				BoardName.brd
				BOM.xls or BOM.csv
			[Major+1.0]
				...
			...
		[lib]
			...
		[res]
			Manufacturer.dru
			Manufacturer.cam