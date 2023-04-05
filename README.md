sequenceDiagram
actor Me
participant PizzaRestaurant
Me->>PizzaRestaurant: Hello, I want to order special pizza.
PizzaRestaurant->>Me: The special one, Yeah, 10$.
Me->>PizzaRestaurant: Pay 10$.
loop Carfting pizza
    PizzaRestaurant->>PizzaRestaurant: Carfting with love
end
PizzaRestaurant->>Me: Here you are, the special one
Me->>PizzaRestaurant: Yummy!
PizzaRestaurant->>Me: Thanks, enjoy your pizza!

  
