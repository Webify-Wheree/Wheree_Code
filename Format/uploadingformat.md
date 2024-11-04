# Brand Data Entry System

This README provides an overview of the data entry requirements for brand information, content, images, attributes, and opening hours in the Brand Data Entry System. Each section includes the necessary fields and instructions for completing entries.

---

## Table of Contents
- [Basic Information Entry](#basic-information-entry)
- [Content Entry](#content-entry)
- [Image Entry](#image-entry)
- [Attribute Entry](#attribute-entry)
- [Opening Hours Entry](#opening-hours-entry)

---

## Basic Information Entry
| STT | Field          | Description                       | Required |
|-----|----------------|-----------------------------------|----------|
| 1   | `original_name` | Brand's original name            | Yes       |
| 2   | `englishname`  | Brand name in English            | Yes      |
| 3   | `phone`        | Contact phone number             | No       |
| 4   | `phone_code`   | Phone country code               | No       |
| 5   | `code`         | Unique UUID code for the brand   | Yes      |
| 6   | `yelp_link`    | Source link for brand info       | No       |
| 7   | `latitude`    | Latitude coordinate              | No       |
| 8   | `longitude`    | Longitude coordinate             | No       |
| 9   | `fulladdress`  | Full address of the brand        | Yes      |
| 10  | `rating`       | Brand rating                     | No       |
| 11  | `num_reviews`  | Number of reviews                | No       |
| 12  | `category`     | Main category                    | Yes      |
| 13  | `subcate1`     | Subcategory 1                    | No       |
| 14  | `subcate2`     | Subcategory 2                    | No       |
| 15  | `subcate3`     | Subcategory 3                    | No       |
| 16  | `price_levels` | Price level                      | No       |
| 17  | `emble`        | Embedded map URL                 | No       |
| 18  | `lv0_short`    | Country                          | No       |
| 19  | `lv1`          | Province/City                    | No       |
| 20  | `lv1_short`    | Abbreviation for Province/City   | No       |
| 21  | `lv2_long`     | District/Region                  | No       |
| 22  | `lv3_long`     | Level 3 address                  | No       |
| 23  | `lv4_long`     | Level 4 address                  | No       |
| 24  | `lv5_long`     | Level 5 address                  | No       |
| 25  | `sublocality_long` | Level 6 address            | No       |
| 26  | `map_url`      | Map URL                          | No       |

---

## Content Entry
| STT | Field     | Description                                         | Required |
|-----|-----------|-----------------------------------------------------|----------|
| 1   | `code`    | Brand's unique code                                 | Yes      |
| 2   | `content` | Content to be entered                               | Yes      |
| 3   | `type`    | Content type: `REVIEW` (brand review) or `MAIN` (short description). For sub-pages, use format e.g., `MAIN.S1.P1.C1` | Yes      |

---

## Image Entry
| STT | Field     | Description                               | Required |
|-----|-----------|-------------------------------------------|----------|
| 1   | `code`    | Brand's unique code                       | Yes      |
| 2   | `image`   | Link to the image                         | Yes      |
| 3   | `type`    | Image type: `MENU` (menu image), `IMAGE` (gallery), `MAIN` (primary image).| Yes      |

---

## Attribute Entry
| STT | Field           | Description             | Required |
|-----|-----------------|-------------------------|----------|
| 1   | `code`          | Brand's unique code     | Yes      |
| 2   | `main_feature`  | Main attribute          | Yes      |
| 3   | `feature`       | Sub-attribute           | Yes      |

---

## Opening Hours Entry
| STT | Field         | Description                                   | Required |
|-----|---------------|-----------------------------------------------|----------|
| 1   | `code`        | Brand's unique code                           | Yes      |
| 2   | `day`         | Day of operation (e.g., Monday, Tuesday, etc.)| Yes      |
| 3   | `openingHour` | Opening hour (format `h:m`, e.g., `8:00`)     | No       |
| 4   | `openingType` | Opening time period: AM/PM                    | No       |
| 5   | `closingHour` | Closing hour (format `h:m`, e.g., `20:00`)    | No       |
| 6   | `closingType` | Closing time period: AM/PM                    | No       |
| 7   | `orginal_name` | Brand's original name                    | No       |

> **Note**: Either `openingHour` or `closingHour` must be specified for each entry.

---

## Additional Notes
- Ensure each brand entry adheres to the specified required fields.
- For sub-page formats (content and images), use the format `MAIN.S1.P1.C1` for content and `MAIN.S1.P1.IMG1` for images to maintain organization.

---

This README serves as a guide for entering and managing brand data within the system. Follow the above sections carefully to ensure consistency and accuracy in brand information entry.
