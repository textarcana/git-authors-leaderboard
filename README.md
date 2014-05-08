git-authors-leaderboard
=======================

Shows an ASCII graph of the top Git authors ranked according to commits-per-author.

## Usage

    gnuplot_terminal.sh <path> <days ago>

For example:

    gnuplot_terminal.sh  ~/my-repo 7
    gnuplot_terminal.sh  . 3


## Example output

    $ ./git_authors_leaderboard ~/mediawiki-core/ 3

    Git authors by count of commits since 3 days ago.

      25 jenkins-bot
       6 Timo Tijhof
       4 Translation updater bot
       3 umherirrender
       3 Chad Horohoe



      25 *
         *
         *
         *
      20 *
         *
         *
         *
      15 *
         *
         *
         *
      10 *
         *
         *
         *                 *
       5 *                 *
         *                 *                *                 *                *
         *                 *                *                 *                *
         *                 *                *                 *                *
      jenkins            Timo            Transla           umherir           Chad
