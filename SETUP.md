# Bhavesh GitHub Profile README — fixed setup

1. Put `README.md` in the special profile repository:
   `bhaveshkumbhalwar/bhaveshkumbhalwar`

2. Copy `.github/workflows/profile-cards.yml` and `.github/workflows/readme-arcade.yml`
   into the same repository.

3. Keep the `assets/` and `dist/` folders.

4. Push everything to GitHub.

5. Open **Actions** in the profile repository and run:
   - **Update Profile Cards**
   - **README Arcade**

6. After the first successful runs, the placeholder SVGs are replaced by generated
   self-hosted SVGs. Future scheduled runs refresh them daily.

The README no longer depends on the public GitHub Readme Stats, Profile Trophy,
or Streak Stats image endpoints for its stats section. Stats, streak/activity cards,
and trophies are generated into your own repository by GitHub Actions.
