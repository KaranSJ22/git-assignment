"Act as a database architect. Generate a PostgreSQL compatible SQL schema for a 'Student Campus Shoutout' application. It requires a table named shoutouts.
Fields:

id (UUID, primary key)
sender_nickname (text, optional)
recipient_name (text, required)
message (text, required)
category (text, allow only: 'Thank You', 'Confession', 'Meme')
created_at (timestamp, default to now)
Also, provide a Row Level Security (RLS) policy to allow public insert and public select."
