ID              INT PRIMARY Key NOT_NULL
Marca           VARCHAR(50) NOT_NULL
Modello         Varchar(50) NOT_NULL
Anno            YEAR        NOT_NULL
Chilometraggio  MEDIUMINT   NULL
Colore          VARCHAR(30) NOT_NULL
TipoCarburante  VARCHAR(30) NOT_NULL
TipoCambio      VARCHAR(10) NOT_NULL
Prezzo          INT         NULL
DataInserimento DATE        NULL
Descrizione     TEXT        
Targa           VARCHAR(10) NOT_NULL    UNIQUE
Condizioni      VARCHAR(30) NULL
