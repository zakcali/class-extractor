# class-extractor
extracts entites tagged with "&lt;span class=" from html files

scans directory for all html files, extracts as csv files, adds "extracted" at the beginning of filenames.

examines body of html file, extracts entites only if they are tagged with class=, before extracting, marks plaint texts with class="O" tag for outsider texts. This is a pre-processor for preparing y_pred array to be called from sklearn library functions, classification_report or f1_score

note: google gemini pro 1.5 created main logic of the program
