# SignalDB_Decrypter
This will decrypt a signal database if you have the decryption key in the json file.  The common use case for this would be to have a full forensic image of a computer (windows, mac, linux), and have access to both the config.json and db.sqlite files.

SOURCE:  https://www.linkedin.com/pulse/signal-desktop-digital-forensics-perspective-surya-teja-masanam/

SQLCipher Key: C:\Users\<Username>\AppData\Roaming\Signal\config.json
SQLite DB: C:\Users\<Username>\AppData\Roaming\Signal\sql\db.sqlite
Attachments: C:\Users\<Username>\AppData\Roaming\Signal\attachments.noindex

Signal for Desktop DB locations in different operations systems :

Windows: C:\Users\<Username>\AppData\Roaming\Signal\sql\db.sqlite 

Linux: ~/.config/Signal/sql/db.sqlite

Mac: ~/Library/Application Support/Signal/sql/db.sqlite
