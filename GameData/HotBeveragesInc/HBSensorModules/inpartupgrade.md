MODULE
	{
		name = ModuleSAS
		SASServiceLevel = 0
		moduleIsEnabled = false﻿

		UPGRADES
		{
			UPGRADE
			{
				name__ = SAS_Level_0
				description__ = SAS level 0
				techRequired__ = electrics
				IsAdditiveUpgrade__ = false
				//ExclusiveWith__ = SASb
				SASServiceLevel = 0
				moduleIsEnabled = true
				hideUIwhenUnavailable = false
			}

			UPGRADE
			{
				name__ = SAS_Level_1
				description__ = SAS level 1
				techRequired__ = precisionEngineering
				SASServiceLevel = 1
				moduleIsEnabled = true
				hideUIwhenUnavailable = false
			}

			UPGRADE
			{
				name__ = SAS_Level_2
				description__ = SAS level 2
				techRequired__ = unmannedTech
				SASServiceLevel = 2
				moduleIsEnabled = true
				hideUIwhenUnavailable = false
			}

			UPGRADE
			{
				name__ = SAS_Level_3
				description__ = SAS level 3
				techRequired__ = advUnmanned
				SASServiceLevel = 3
				moduleIsEnabled = true
				hideUIwhenUnavailable = false
			}
		}
	}