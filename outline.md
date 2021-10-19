job:
 -title
 -location
 -job_type
 -description
 -published_at
 -vacancy
 -salary
 -category
 experience

 apply job
 post job

blog:
 -title
 -description
 -created at
 -category
 -tags
 -author

 -search
 -comment
 -recent posts

contact:
  -home

 login:


relationship django:
   one to many = [user and post]
   many to many =[user and group]
   one to one =[user and profile]
