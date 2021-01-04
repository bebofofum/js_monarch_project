# App used by Monarch to log sightings and details of kaiju/titans as they appear.
 
# Using 2 models: Kaiju and Sightings

# Kaiju or Titan model will has_many Sightings.
# Kaiju will have t.string img_src, t.string nickname, t.string size, t.text description 

# Sightings model will belongs_to Kaiju
# Sightings will have t.string location (just going to do maybe country or city), and t.datetime sighting_datetime

