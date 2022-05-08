# Blog
blog built with flask (Flask, render_template, request, url_for, redirect, flash, abort) and Bootstrap;
database is created and managed with SQLAlchemy and relationship;
user register and login are managed with flask_login (UserMixin, login_user,current_user,logout_user, and LoginManager);
create and edit posts as well as leave comments via ralationship, Gravatar, FlaskForm, wtforms (StirngField, SubmitField, PasswordField), wtforms.validators (DataRequired, URL) and CKEditorField;
user password is protected via werkzeug.security (generate_password_hash and check_password_hash);
admin-only function is implemented via wraps;
contact website owner via email by smtplib
