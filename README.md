# Trucking-Job

Trucking job for Sandbox's version of Mythic framework.

Requires Sandbox version of Mythic framework.

You can rename the files as you wish and place them within the appropriate folders within sandbox-labor (client/server/config)

You must also add the following to sandbox-labor > server > startup.lua (edit the pay & reputation as you wish)

- Labor.Jobs:Register("Trucking", "Trucking", 0, 1500, 100, false, {
        { label = "Rank 1", value = 1500 },
        { label = "Rank 2", value = 3000 },
        { label = "Rank 3", value = 7000 },
        { label = "Rank 4", value = 10000 },
        { label = "Rank 5", value = 12000 },
        { label = "Rank 6", value = 15000 },
        { label = "Rank 7", value = 18000 },
        { label = "Rank 8", value = 21000 },
        { label = "Rank 9", value = 24000 },
        { label = "Rank 10", value = 30000 },
        { label = "Rank 11", value = 35000 },
        { label = "Rank 12", value = 40000 },
        { label = "Rank 13", value = 45000 },
        { label = "Rank 14", value = 50000 },
        { label = "Rank 15", value = 55000 },
        { label = "Rank 16", value = 60000 },
        { label = "Rank 17", value = 65000 },
        { label = "Rank 18", value = 70000 },
        { label = "Rank 19", value = 75000 },
        { label = "Rank 20", value = 80000 },
    })