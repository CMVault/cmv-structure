# API ROUTES - Camera Manual Vault
Generated: 8/3/2025, 5:43:25 PM

## Available Endpoints

### GET Requests

#### `GET /api/cameras`
- File: server.js
- Description: Camera-related endpoint

#### `GET /api/camera/:id`
- File: server.js

#### `GET /api/search`
- File: server.js

#### `GET /api/stats`
- File: server.js

#### `GET /api/image-proxy`
- File: server.js
- Description: Image processing endpoint

#### `GET /images/cameras/:filename`
- File: server.js

#### `GET /camera/:id`
- File: server.js

#### `GET /camera-blog`
- File: server.js

#### `GET /privacy`
- File: server.js

#### `GET /terms`
- File: server.js

#### `GET /dmca`
- File: server.js

#### `GET /attribution`
- File: server.js

#### `GET /legal`
- File: server.js

### POST Requests

#### `POST /api/camera-finder`
- File: server.js

## Database Schema

### Table: cameras

| Column | Type | Constraints |
|--------|------|-------------|
| id | TEXT | PRIMARY KEY |
| brand | TEXT | NOT NULL |
| model | TEXT | NOT NULL |
| fullName | TEXT |  |
| category | TEXT |  |
| releaseYear | INTEGER |  |
| price | REAL |  |
| imageUrl | TEXT |  |
| localImagePath | TEXT |  |
| imageVerified | BOOLEAN | DEFAULT 0 |
| imageLastChecked | DATETIME |  |
| manualUrl | TEXT |  |
| specs | TEXT |  |
| features | TEXT |  |
| lastUpdated | DATETIME | DEFAULT CURRENT_TIMESTAMP |

### Table: image_cache

| Column | Type | Constraints |
|--------|------|-------------|
| url | TEXT | PRIMARY KEY |
| localPath | TEXT |  |
| contentType | TEXT |  |
| size | INTEGER |  |
| cachedAt | DATETIME | DEFAULT CURRENT_TIMESTAMP |
| lastAccessed | DATETIME | DEFAULT CURRENT_TIMESTAMP |

