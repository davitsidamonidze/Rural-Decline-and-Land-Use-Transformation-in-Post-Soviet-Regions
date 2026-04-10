# Rural-Decline-and-Land-Use-Transformation-in-Post-Soviet-Regions
depopulation abandoned land forest regrowth / degradation
data = pd.read_csv("data/population_land.csv")

data["change"] = data["population_2020"] - data["population_2000"]

print(data[["region", "change"]])
