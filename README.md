# django-project2
 - If you have been accustomed to having a signature at the end of your email messages, you may want to do the same for your blog. A signature is a bit of text, like your contact information or a favourite quote, that is automatically added at the end of the messages you send.
Follow these steps:
- Edit your models.py and add a new field called signature. This field will follow the same syntax as your title:
signature = models.CharField(max_length=140)
- Place the field in-between your body and date fields.
- In addition to max_length, add a new parameter called default and set this to whatever you like (your name, favourite quote etc.). This should be a string.
- Make the necessary migrations.
