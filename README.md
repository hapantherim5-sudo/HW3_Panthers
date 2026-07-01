# HW3_Panthers

## הוראות הרצה

בהתאם למייל של נעמי, ניתן להריץ את הפרויקט גם ללא מפתחות Gemini ו־Firebase. במקרה כזה הממשק יעלה, אך תכונות ה־AI ושמירת הנתונים הקבועה לא יעבדו במלואן.

לבדיקה מלאה יש להוסיף ב־Google Colab תחת **Secrets**:

### Gemini

1. ליצור API Key ב־Google AI Studio.
2. להוסיף Secret בשם:

```text
GEMINI_API_KEY
```

### Firebase

1. להיכנס ל־Firebase Console.
2. לעבור אל **Project Settings → Service Accounts**.
3. לבחור **Generate New Private Key**.
4. להעתיק את תוכן קובץ ה־JSON ולהוסיף אותו כ־Secret בשם:

```text
FIREBASE_SERVICE_ACCOUNT
```

לאחר הוספת המפתחות יש להריץ מחדש את המחברת.
