# DashboardSimple

We will create a Dashboard with Angular and Angular Material with only 6 commands.

1 - Create the project with angular-cli
  ng new dashboar-simple

2 - Install the Material angular
  ng add @ angular / material

3 - Create the menu using the schematic
  ng g @ angular / material: nav menu

4 - Customize the menu
  <ng-content></ng-content>

5 - Create the interior of the dashboard
  ng g @ angular / material: dashboard dashboard
  
6 - Integrate the interior to the menu
<app-menu>
  <app-dashboard></app-dashboard> 
</app-menu>
