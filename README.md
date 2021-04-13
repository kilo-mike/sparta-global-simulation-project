# SpartaGlobalSimulationProject

## Requirement 1

The tracker needs to be able to track time in a consistent way.

The program starts by asking how long the simulation will run for.

Every month, a random number of trainees are generated wanting to be trained (20 -30).

Every 2 months, Sparta global opens a training centre. They open instantly and can take trainees every month.

A centre can train a max of 100 trainees and takes a random number of trainees every month. (0 - 20 trainees per month up to the max capacity).

If a centre is full, trainees can be moved to any other centre which is not full.

If all centres are full, the trainees go onto a waiting list. This list must be served first before new trainees are taken.

At the end of the simulation, output should show:
  - Number of open centres
  - Number of full centres
  - Number of trainees currently training
  - Number of trainees on the waiting list

## Our Definition of Done &#x2611;

#### Code is peer-reviewed

#### Code is checked in

#### Code is deployed to test environment

#### Code/feature passes regression testing

#### Code/feature passes smoke testing

#### Code is documented

#### Help documentation is updated

#### Feature is OK’d by stakeholders


## Objects
Trainee(final id++, final joinMonth)

## Collections
ArrayList<Trainee> centre (max capacity 100)
ArrayList<Trainee> waitingList

## Interfaces
- int numberOfCentres();
- int numberOfOpenCentres();
- int numberOfFullCentres();
- int numberOfTraineesInTraining();
- int numberOfTraineesInWaiting();
  
