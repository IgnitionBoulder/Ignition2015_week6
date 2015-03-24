- Answer these CodeLearn Rails Models exercise questions:
  - What model method allows you to make a new model instance and save it?
  	
  	You can do this one of two ways:
  	the .create model method allows you to do this in one step
  		model_instance_name = ModelClassName.create
  	the .new model method also instantiates a new model, but does not save it. This method can be used when you want to assign different attributes to the instance. Additionally, to save it to the database, you have to run the .save model method to add it to the database.
  		model_instance_name = ModelClassName.new
  		model_instance_name.save

  - If I wanted to find all `Bulldog`s with the `breed` of `'English'`, what line in Ruby would I execute?

  	bulldogs = Bulldog.where(breed: "English")

  - How do you delete all instance of a certain model?

  	model_instance_name.destroy
  	
- RailsTutorial Ch. 6
  - Link to `sample_app` repo: [my repo](https://github.com/Victorrent/Chapter_6_project)
  - Link to app on Heroku: [my app](https://serene-scrubland-7536.herokuapp.com/)
