# Create_Display_Journal_Table_View

## Istruzioni

per ogni schema, lanciare CREATE_DISPLAY_JOURNAL_TABLE_VIEW per creare la stored procedure

successivamente, eseguire la chiamata alla sp per ogni table che si vuole monitorare, di cui si vuole creare la view di interrogazione giornali

chiamare la view generata
SELECT * FROM MAG80DAT.YAUDMG00FL FETCH FIRST 10 ROWS ONLY