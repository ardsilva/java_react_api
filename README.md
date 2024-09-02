# Spring boot + ReactJS API applicantion

## Pre conditions
java: >=17
<br />
node: >=18
<br />
react: >=16
<br />
## Init backend
```
cd backend
./nvmw spring-boot:run
```
You should see your server up and in console
```
...
Group(id=1, name=Seattle JUG, address=null, city=null, stateOrProvince=null, country=null, postalCode=null, user=null, events=[Event(id=1, date=2022-09-13T17:00:00Z, title=Micro Frontends for Java Developers, description=JHipster now has microfrontend support!, attendees=[])])
Group(id=2, name=Denver JUG, address=null, city=null, stateOrProvince=null, country=null, postalCode=null, user=null, events=[])
Group(id=3, name=Dublin JUG, address=null, city=null, stateOrProvince=null, country=null, postalCode=null, user=null, events=[])
Group(id=4, name=London JUG, address=null, city=null, stateOrProvince=null, country=null, postalCode=null, user=null, events=[])
```

## Init frontend
```
cd frontend
npm install
npm run start
```
You should check the page on `http:localhost:3000`
![image](https://github.com/user-attachments/assets/d344a465-4f5e-4a7a-8f0f-abc95b673609)

When you go to `http:localhost:3000/groups`
![image](https://github.com/user-attachments/assets/a167ba18-0858-4d4d-8bc8-2c5499717195)

