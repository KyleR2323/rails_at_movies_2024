Movies table:
- id, title, year, duration, description, average_vote, production_company_id

Production_Companies Table (1 to many)
- id, Name

movies_genre table (join table)
- movie_id, genre_id

genres table (many to many with movies)
- id, Name
