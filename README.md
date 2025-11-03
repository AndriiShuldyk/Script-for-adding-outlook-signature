# Інтсрукція
1. Запустить файл ".\SetupEmailSignatureInOutlook.ps1" від імені звичайного користувача.
2. На пункті "Signature configuration choices:" вибрати 4 та вставити шлях до html файлу.
3. На питанні "Are you sure to deploy the signature with this template?" вибрати "Y"
4. Потім необхідно вибрати які атрибути присутні в файлі підпису. Наприклад "1,2,4,7"
5. При питанні "Enter the DisplayName as it appears in the provided HTML:" вписати атрибут "%%DisplayName%%"
6. На пункті "User-Based Email Signature Deployment:" вибрати "2" якщо є csv файл зі списком поштових ящиків або "3" для всіх користувачів

# Instructions
1. Run the file “.\SetupEmailSignatureInOutlook.ps1” as a regular user.
2. Under “Signature configuration choices:”, select 4 and paste the path to the html file.
3. When asked “Are you sure to deploy the signature with this template?”, select “Y”.
4. Then you need to select which attributes are present in the signature file. For example, “1,2,4,7”.
5. When asked “Enter the DisplayName as it appears in the provided HTML:”, enter the attribute “%%DisplayName%%”.
6. Under “User-Based Email Signature Deployment:”, select ‘2’ if there is a csv file with a list of mailboxes or “3” for all users.
