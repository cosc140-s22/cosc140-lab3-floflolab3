# COSC140 lab 3

## Answers to the five questions at the end of the lab description

1.
>>> p1 = Product(name= 'stuffed shark', description = 'soft, but with pointy teeth', price = '45.00', minimum_age_appropriate = "2", maximum_age_appropriate = '43')
>>> p1.save()

2. 
>>> Product.objects.all ()

3.
>>> p1 = Product.objects.get(id=6)
>>> p1.price=22.50
>>> p1.save()
>>> Product.objects.all()

4. 
>>> Product.objects.get(id=6).delete()
>>> Product.objects.all ()

NULL??? nothing shows up! blank

5.
objects = Product.objects.filter(price__lt =10).filter(name__icontains="stuffed")

## Lab feedback

 * How long did you spend on this lab?
a long time 
 * What did you think about it?  What was good?  What could be improved?
i liked it 
## Feedback

Once you commit and submit your work to Github, I'll update this section with feedback.

