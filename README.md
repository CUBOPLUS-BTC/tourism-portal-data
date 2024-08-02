# Tourism Portal

## Project Structure

This repository contains the necessary resources for the El Salvador tourism portal. Below is a detailed structure of the folders and their purpose.

### assets/

- `images/`: Contains images categorized by destinations and general service categories.
  - `destinations/`: Specific images for each destination, organized by destination folder.
  - `categories/`: Images organized by general service categories such as hotels, restaurants, cafes, activities, etc.
- `json/`: JSON files listing tourism destinations and categorized services, supporting multiple languages.
  - `destinations/`: Specific JSON files for each destination with subfolders for languages (`es.json` for Spanish and `en.json` for English).
  - `categories/`: JSON files for each general service category with a list of all items in that category.

### onboard/

- JSON files listing useful resources for tourists.

### btc_communities/

- Individual folders for each Bitcoin community with their respective resources (images, JSON for languages, URLs, events, and articles).

## How to Contribute

1. **Add New Content**:

   - **Images**: Add new images in the appropriate folder within `assets/images/`.
   - **Data**: Edit the corresponding JSON files in `assets/json/`.

2. **Update Existing Content**:

   - **Edit Images**: Replace existing images with new ones.
   - **Edit Data**: Modify the corresponding JSON files with the new information.

3. **Submit Changes**:
   - Commit the changes made and push to the main branch of the repository.

## Considerations

- Ensure all images are optimized for the web with .webp format.
- Maintain consistency in the structure of the JSON files.
- For multilingual support, ensure that each destination and community has JSON files for both English and Spanish.

## Example Structure

```plaintext
tourism-portal/
│
├── assets/
│   ├── images/
│   │   ├── destinations/
│   │   │   ├── juayua.webp
│   │   │   ├── el_zonte.webp
│   │   │   ├── el_tunco.webp
│   │   │   └── ...
│   │   ├── categories/
│   │   │   ├── companies/
│   │   │   │   ├── chivo.webp
│   │   │   │   ├── dito_banx.webp
│   │   │   │   └── ...
│   │   │   ├── accomodation/
│   │   │   │   ├── paloverde_zonte.webp
│   │   │   │   ├── barcelo.webp
│   │   │   │   └── ...
│   │   │   ├── restaurants/
│   │   │   │   ├── cadejo_montana.webp
│   │   │   │   ├── cowboys.webp
│   │   │   │   └── ...
│   │   │   ├── cafes/
│   │   │   │   ├── fulanos_downtown.webp
│   │   │   │   ├── cherito_cafe.webp
│   │   │   │   └── ...
│   │   │   ├── activities/
│   │   │   │   ├── surf_para_todos.webp
│   │   │   │   ├── santa_ana_volcano_hiking.webp
│   │   │   │   └── ...
│   │   │   └── ...
│   └── json/
│       ├── destinations/
│       │   ├── juayua/
│       │   │   ├── en.json
│       │   │   ├── es.json
│       │   ├── el_zonte/
│       │   │   ├── en.json
│       │   │   ├── es.json
│       │   ├── el_tunco/
│       │   │   ├── en.json
│       │   │   ├── es.json
│       │   └── ...
│       ├── categories/
│       │   ├── accomodation.json
│       │   ├── restaurants.json
│       │   ├── cafes.json
│       │   ├── activities.json
│       │   └── ...
│
├── onboard/
│   ├── bitcoin_atms.json
│   ├── wallets.json
│   ├── transportation.json
│   ├── accommodation.json
│   ├── restaurants.json
│   ├── cafes.json
│   ├── laundry.json
│   ├── vets.json
│   ├── communication.json
│   ├── healthy.json
│   └── emergency.json
│
├── btc_communities/
│   ├── btc_communities.json
│   ├── bitcoin_beach/
│   │   ├── images/
│   │   │   ├── articles/
│   |   │   │   ├── article_01.webp
│   |   │   │   ├── article_02.webp
|   |   |   |   └── article_03.webp
│   │   │   ├── leaders/
│   |   │   │   ├── mike.webp
│   |   │   │   ├── pete.webp
|   |   |   |   └── roman.webp
│   │   │   ├── community_01.webp
│   │   ├── en.json
│   │   └── es.json
│   ├── berlin_sv/
│   │   ├── images/
│   │   │   ├── articles/
│   |   │   │   ├── article_01.webp
│   |   │   │   ├── article_02.webp
|   |   |   |   └── article_03.webp
│   │   │   ├── leaders/
│   |   │   │   ├── gerardo.webp
│   |   │   │   ├── evelyn.webp
|   |   |   |   └── charlie.webp
│   │   │   ├── community_01.webp
│   │   ├── en.json
│   │   └── es.json
│   └── ...
│
└── README.md
```
