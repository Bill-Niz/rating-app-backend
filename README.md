# Rating App Backend
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FBill-Niz%2Frating-app-backend.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FBill-Niz%2Frating-app-backend?ref=badge_shield)


Backend for rating application
* Server api :  https://rating-serve.herokuapp.com/
* Client : https://bill-niz.github.io/rating-app/

## Usage

Run `node index.js` 

## Endpoints

#### Authentification

* POST `/api/v1/register`
* POST `/api/v1/login`


#### Application

* GET `/api/v1/applications`
* GET `/api/v1/application/:id`
* POST `/api/v1/application/`


#### Feedback

* POST `/api/v1/feedbacks`
* POST `/api/v1/feeback/application/:id`


#### Comment

* POST `/api/v1/comments`
* POST `/api/v1/comment/feedback/:id`
* POST `/api/v1/comment/notation/:id`

## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FBill-Niz%2Frating-app-backend.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FBill-Niz%2Frating-app-backend?ref=badge_large)