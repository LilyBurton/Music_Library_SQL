Nouns

album, title, release_year, artist_id

| Record  |  Properties |
| album   |  title      |
          | release_year|
          | artist_id   |

CREATE TABLE albums (
  id SERIAL PRIMARY KEY,
  title text,
  release_year int,
);