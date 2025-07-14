# constellation
Enumerate type for constellations for Python

 ## Usage

```python
from constellation import Constellation
# Example usage
print(Constellation.Andromeda)  # Directly access the enum member
print(Constellation['Andromeda'])  # Access by name
print(Constellation['And'])  # Access by abbreviation

# Accessing name, abbreviation, and value
print(Constellation.Andromeda.name)  # 'Andromeda'
print(Constellation.Andromeda.abbr)  # 'And'
print(Constellation.Andromeda.value)  # 1 (Alphabetical order of enum members)

# Iterate through all constellations
for constellation in Constellation:
    print(constellation)
```