import statistics

temperature = [30, 31, 29, 32, 33, 34, 35, 36, 32, 31]
humidity = [40, 42, 38, 45, 50, 48, 47, 46, 44, 43]
aqi = [90, 85, 88, 92, 95, 100, 105, 98, 96, 93]

def analyze(data, name):
    avg = statistics.mean(data)
    med = statistics.median(data)
    return f"{name} -> Avg: {avg}, Median: {med}"

results = [
    analyze(temperature, "Temperature"),
    analyze(humidity, "Humidity"),
    analyze(aqi, "AQI")
]

# Store results
with open("results.txt", "w") as file:
    for line in results:
        file.write(line + "\n")

print("Analysis stored in results.txt")
