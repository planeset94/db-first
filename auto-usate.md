## table name: Auto usate

- id                    BIGINT PRIMARY KEY UNIQUE AUTO_INCREMENT  NOTNULL 
- modello               VARCHAR(50)  NOTNULL    
- marca                 VARCHAR (30) NOTNULL    
- sensori parcheggio    TINYINT NULL
- accessorio1           TINYINT NULL
- accessorio2           TINYINT NULL
- accessorio3           TINYINT NULL
- accessorio4           TINYINT NULL
- anno                  YEAR NOTNULL    
- km percorsi           MEDIUMINT NULL
- revisionata           TINYINT NOTNULL    
- numero proprietari    TINYINT NOTNULL    
- prezzo vendita        DECIMAL(10,2) NULL
