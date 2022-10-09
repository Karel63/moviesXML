# Movies

## Name

Simple-movies.XML

## Specification

Code in UTF-8

## Example

[Click here](movies.XML)

# Help

### `<movies>`
- **Main atribute**
- Atribute for all movies

### `<movie>`
- Atribute for one movie
- Child to `<movies>`
- Atributes:
    - `id`: identifivator
    - `name`: name of the movie
    - `year`: release date of the movie

### `<genres>`
- **Main atribute** for the movie genres
- Child to `<movie>`

### `<genre>`
- Atribute for one genre
- Child to `<genres>`
- Atributes:
    - `id`: identifivator
    - `name`: name of the genre

### `<country>`
- Atribute for the country where the movie was released
- Child to `<movie>`
- Atributes:
    - `id`: identifivator
    - `name`: name of the country
