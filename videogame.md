
<!-- 
Istruzioni:
Create un file di testo per descrivere un database di un negozio di videogiochi.
Strutturate il file come fatto oggi in classe.  Specificate: il nome del database, la tabella e le potenziali colonne con i tipi di dato.
 -->

# database name : VideoGames
# column : 
- Id: BIGINT | NOTNULL | AUTO_INCREMENT | PRIMARY_KEY | UNIQUE 
- Nome: VARCHAR(50) | NULL 
- PEGI: TINYINT | NULL | DEFAULT(3)
- Data_di_uscita: DATE | NULL
- Prezzo_Nuovo: SMALLINT | NULL
- Prezzo_Usato: SMALLINT | NULL
- Trailer: TEXT | NULL 
- Piattaforma: VARCHAR(50) | NULL
- Genere: TEXT | NULL
- Data_di_rilascio: DATE | NULL
- Disponibile: TINYINT | NULL | DEFAULT(0)
- Sofware_house: VARCHAR(30) | NULL
- Sviluppatore: VARCHAR(30) | NULL
