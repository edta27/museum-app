#Museum-app

##Angular App

This is a very sample app used to show people hours and rate to the musemum. 

Sample Code

```
      <section id="generalInfo" ng-controller="GeneralInfoController as info">
        <h2>General Info:</h2>
        <h3>Hours:</h3>
        <ul>
          <li ng-repeat="(key, value) in info.hours">
            <strong> {{key}}:</strong> {{ value }}
          </li>
        </ul>
        <h3>Suggested Admission:</h3>
        <ul>
          <li ng-repeat="(key, value) in info.admission">
            {{key}} - {{value}}
          </li>
        </ul>
      </section>
```