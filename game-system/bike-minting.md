# Bike Minting

### Bike-Minting

Bike-Minting Event (BME) is when users use 2 Bicycles they own as a blueprint to “breed”, producing a Shoebox in the process. For reference, the 2 Bicycles will be called Vintages (Parents). Both Vintages need to be in the user’s possession (not under lease) and have full durability to begin an SME.

Users can then select a Bicycle, by heading to the **Mint** tab, choosing the Bicycle to “breed” with, and pressing **Mint** to proceed. The user will instantly receive a Shoebox that can be opened immediately.

Users can perform a maximum of 7 SMEs per Bicycle. The higher SME count a Bicycle has, the more PAS/PAL it will cost. Shoe-Minting costs for each Vintage is calculated separately and added together for the final Minting cost.

Shoe-Minting has a 48-hour cool down for both Vintages – Bicycles can still be used for movement.

### Bike-Minting Costs

1. Common – PAS
2. Uncommon – PAS
3. Rare – PAS + PAL
4. Epic – PAS + PAL
5. Legendary – PAS + PAL

The first two Shoe-Minting costs the same. Shoe-Minting has a chance to drop one extra Shoeboxes. The higher the Mint count, the higher the chance to drop multiple Shoeboxes.

Shoebox Quality is determined by the Vintage Bicycle's Quality:

| **Vintage 1 Quality** | **Vintage 2 Quality** | **Common Shoebox %** | **Uncommon Shoebox %** | **Rare Shoebox %** | **Epic Shoebox %** | **Legendary Shoebox %** |
| --------------------- | --------------------- | -------------------- | ---------------------- | ------------------ | ------------------ | ----------------------- |
| Common                | Common                | 100                  | 0                      | 0                  | 0                  | 0                       |
| Common                | Uncommon              | 50                   | 49                     | 1                  | 0                  | 0                       |
| Common                | Rare                  | 50                   | 0                      | 49                 | 1                  | 0                       |
| Common                | Epic                  | 50                   | 0                      | 0                  | 49                 | 1                       |
| Common                | Legendary             | 50                   | 0                      | 0                  | 0                  | 50                      |
| Uncommon              | Uncommon              | 0                    | 98                     | 2                  | 0                  | 0                       |
| Uncommon              | Rare                  | 0                    | 49                     | 50                 | 1                  | 0                       |
| Uncommon              | Epic                  | 0                    | 49                     | 1                  | 49                 | 1                       |
| Uncommon              | Legendary             | 0                    | 49                     | 1                  | 0                  | 50                      |
| Rare                  | Rare                  | 0                    | 0                      | 98                 | 2                  | 0                       |
| Rare                  | Epic                  | 0                    | 0                      | 49                 | 50                 | 1                       |
| Rare                  | Legendary             | 0                    | 0                      | 49                 | 1                  | 50                      |
| Epic                  | Epic                  | 0                    | 0                      | 0                  | 98                 | 2                       |
| Epic                  | Legendary             | 0                    | 0                      | 0                  | 49                 | 51                      |
| Legendary             | Legendary             | 0                    | 0                      | 0                  | 0                  | 100                     |

Users will get a new Bicycle once they open the Shoebox, with the Bicycle Quality determined by the Shoebox Quality:

| **Shoebox Quality** | **Common Bicycle %** | **Uncommon Bicycle %** | **Rare Bicycle %** | **Epic Bicycle %** | **Legendary Bicycle %** |
| ------------------- | -------------------- | ---------------------- | ------------------ | ------------------ | ----------------------- |
| **Common**          | 97                   | 3                      | 0                  | 0                  | 0                       |
| **Uncommon**        | 25                   | 73                     | 2                  | 0                  | 0                       |
| **Rare**            | 0                    | 27                     | 71                 | 2                  | 0                       |
| **Epic**            | 0                    | 0                      | 30                 | 68                 | 2                       |
| **Legendary**       | 0                    | 0                      | 0                  | 35                 | 65                      |

**Note: Epic Bicycle drop is disabled at the moment even there is 2% drop rate from Opening Rare Shoebox**

The new Bicycle type is determined by the two Vintage Bicycle types:

| **Vintage 1 Type** | **Vintage 2 Type** | **Walker %** | **Jogger %** | **Runner %** | **Trainer %** |
| ------------------ | ------------------ | ------------ | ------------ | ------------ | ------------- |
| Casual             | Casual             | 85           | 6            | 6            | 3             |
| Casual             | Recreational       | 45           | 45           | 7            | 3             |
| Casual             | Warrior            | 45           | 7            | 45           | 3             |
| Casual             | Racer              | 80           | 6            | 6            | 8             |
| Recreational       | Recreational       | 6            | 85           | 6            | 3             |
| Recreational       | Warrior            | 7            | 45           | 45           | 3             |
| Recreational       | Racer              | 6            | 80           | 6            | 8             |
| Warrior            | Warrior            | 6            | 6            | 85           | 3             |
| Warrior            | Racer              | 6            | 6            | 80           | 8             |
| Racer              | Racer              | 25           | 25           | 25           | 25            |

The new Sneaker's Socket type is determined by two Vintage Sneakers' Socket types:

| **Vintage 1**     | **Vintage 2**     | **Efficiency Socket %** | **Luck Socket %** | **Comfort Socket %** | **Durability Socket %** |
| ----------------- | ----------------- | ----------------------- | ----------------- | -------------------- | ----------------------- |
| Efficiency Socket | Efficiency Socket | 85                      | 5                 | 5                    | 5                       |
| Efficiency Socket | Luck Socket       | 45                      | 45                | 5                    | 5                       |
| Efficiency Socket | Comfort Socket    | 45                      | 5                 | 45                   | 5                       |
| Efficiency Socket | Durability Socket | 45                      | 5                 | 5                    | 45                      |
| Luck Socket       | Luck Socket       | 5                       | 85                | 5                    | 5                       |
| Luck Socket       | Comfort Socket    | 5                       | 45                | 45                   | 5                       |
| Luck Socket       | Durability Socket | 5                       | 45                | 5                    | 45                      |
| Comfort Socket    | Comfort Socket    | 5                       | 5                 | 85                   | 5                       |
| Comfort Socket    | Durability Socket | 5                       | 5                 | 45                   | 45                      |
| Durability Socket | Durability Socket | 5                       | 5                 | 5                    | 85                      |

### Bike-Minting Variation

Bicycle Attributes are randomized according to their quality, regardless of their Vintage’s Attributes.
