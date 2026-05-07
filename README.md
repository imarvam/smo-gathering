# SMO Gathering - Strategic Planning Game

This project is a web-based game for strategic planning. It is integrated with Supabase to fetch questions dynamically.

## Deployment to Vercel

To correctly connect the database after deploying to Vercel, follow these steps:

1. Go to your project settings in **Vercel**.
2. Navigate to **Environment Variables**.
3. Create a new variable:
   - **Key**: `SUPABASE_ANON_KEY`
   - **Value**: (Insert your Supabase **Anon Public Key** here)
4. Redeploy the project.

The game will automatically fetch questions from the `game_questions` table in your Supabase project.

## Database Setup

See [supabase_setup_guide.md](./supabase_setup_guide.md) for the SQL commands to set up the database.
