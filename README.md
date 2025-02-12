in the script itself is a manual array
you can add your movie list here

   // *** CUSTOM BACKUP LIST (EDIT THIS ARRAY DIRECTLY) ***
    const customHiddenTitlesBackup = [
        // Add your backup titles here, e.g.:
        'The Shawshank Redemption',
        'The Godfather',
        'The Dark Knight',
        '12 Angry Men',
        'Schindler\'s List'
    ];

    and then on the UI side of the site is a red X to press on a money to quickly add it to a temp array.
    Evenutally, take that temp array and just paste it into this manual array as a means of Backup.

    when you clear cache, the temp array is gone, but the manual array remains. so it's just a way of backup.
