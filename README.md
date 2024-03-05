# ML-Olympiad-UIU-2024
#Plans 
1 . # EDA : 
* missing value er jonno 2 ta file toiri kore alada alada predict kora . then avarage kora .
Converting PoolQC into binary values: 1 for presence, 0 for absence
all_df.loc[~all_df["PoolQC"].isnull(), "PoolQC"] = 1
all_df.loc[all_df["PoolQC"].isnull(), "PoolQC"] = 0
*
