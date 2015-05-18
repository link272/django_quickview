django-quickview

quick examples are better, then complex explanation.
If you want to keep your code clean, Quickviews are made for you.
I try to make it as much KISS as I can.

examples:

	class CreateCarView(QuickView):
		fields = '__all__'
		url_redirect = 'cars-list'
		
  
		get(self):
			self.form()
			self.template()
	
		post(self):
			self.saveform()
			self.redirection()



