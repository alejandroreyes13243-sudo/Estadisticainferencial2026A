import kagglehub

# Download latest version
path = kagglehub.dataset_download("jeanpierrebetancourt/houses-price-web-scraping-mexico")

print("Path to dataset files:", path)
