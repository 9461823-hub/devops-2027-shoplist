#הורדת אימייג' של פייטון
FROM python:3.11-slim
#פתיחת תיקית עבודה
WORKDIR /app
#העתקת והתקנת הסריות הדרושת
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
#העתקת הקוד הדרוש
COPY app.py .
#חשיפת הפורט הדרוש
EXPOSE 5000
#הרצת הפקודות המתאימות
CMD ["python", "app.py"]
