# waterline-self-driving-car

`waterline-self-driving-car` takes the same flexible, powerful, minimal ORM API
you know and love, and extends it so it is able to drive cars.

Just set `waterline-self-driving-car` as your adapter in
`config/connections.js`, turn the key in the ignition to ON, and turn on Harry
Potter 2! Nothing else you need to worry about.

## Example

```javascript
var car = new Car({wheels: 4});
// Save the car to the database
car.save();

// Detect objects in the roadway
car.findOne({deer: true})

// Turn left
car.update({direction: -90})

// Stop car
car.update({speed: 0})
```

## Is it safe?

Maybe! I heard some really good engineers at Chrome were working on V8. Also
the other cars on the road have really attentive drivers

As far as Im concerned - their are fatal accidents every 10 million miles and
the average person only drives 100,000 in there lifetime. So we have a lot of
room to play with

## But cars need to respond to really complex, emergent behavior

That may be, but Waterline has a set of API's that are really easy to get
started with. Why worry whether the keys are actually under the lamppost? At
least you can see really well

### Errata

Sometimes the car will report the speed as `NaN`, we're working on it.
