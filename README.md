# Tourism Portal

## Project Structure

This repository contains the necessary resources for the El Salvador tourism portal. Below is a detailed structure of the folders and their purpose.

### assets/

- `assets/`: This is the bank of images.
  - `destinations/`: Specific images for each destination, organized by destination folder.
  - `categories/`: Images organized by general service categories such as hotels, restaurants, cafes, activities, etc.
  - `communities/`: Images organized by Bitcoin communities and resources needed.

### destinations/

- `destinations/`: Text data and urls to show in the website.
   - `en.json / es.json`: listing information to show in the destinations section.
   - `template/`: Template to duplicate and add a new destination.
   - `[id]`: Conten of a destination.

## How to Contribute

1. **Add New Content**:

   - **Images**: Make sure to add new images on `assets/destinations`, `assets/categories/[category]` or `assets/communities/[community]` with a unique and scalable name using snake_case.
   - **Data**: Edit the corresponding JSON file in `destinations/en.json` <- this files serve to show it on the destinations section. Then you must create the destination info at `destinations/[destination_id]/en.json`, copy and paste the template folder and change its name to add a new one.

2. **Update Existing Content**:

   - **Edit Images**: Replace existing images with new ones, use same id.
   - **Edit Data**: Modify the corresponding JSON files with the new information.

3. **Submit Changes**:
   - Create a new branch with your changes, name it as `add-destination-[id]` if you're adding new destination, commit, and create a pull request to main branch.
   - `add-event-[title]` if the addition is an event.
   - `update-destination-[id]` if you're updating content of a destination.

## Considerations

- Ids' must be in snake_case.
- Ensure all images are optimized for the web with .webp format.
- Maintain consistency in the structure of the JSON files.
- For multilingual support, ensure that each destination has JSON files for both English and Spanish.

## Example Structure

```plaintext
tourism-portal/
│
├── assets/
│   ├── destinations/
│   │    ├── juayua.webp
│   │    ├── el_zonte.webp
│   │    ├── el_tunco.webp
│   │    └── ...
│   ├── categories/
│   │    ├── accomodation/
│   │    │   ├── paloverde_zonte.webp
│   │    │   ├── barcelo.webp
│   │    │   └── ...
│   │    ├── restaurants/
│   │    │   ├── cadejo_montana.webp
│   │    │   ├── cowboys.webp
│   │    │   └── ...
│   │    ├── cafes/
│   │    │   ├── fulanos_downtown.webp
│   │    │   ├── cherito_cafe.webp
│   │    │   └── ...
│   │    ├── activities/
│   │    │   └── surfing/
│   │    │        ├── los_tres_hermanos.webp
│   │    │        └── ...
│   │    └── ...
│   └── communities/
|        └── bitcoin_beach/
│            ├── thumbnail.webp
│            ├── logo.webp
│            └── chumbera.webp
|
├── destinations/
│   ├── en.json
│   ├── es.json
│   ├── templates/
│   │   ├── en.json
│   │   └── es.json
│   ├── el_zonte/
│   │   ├── en.json
│   │   └── es.json
│   └── ...
└── README.md
```
