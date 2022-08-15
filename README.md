# investigate_appointment_dataset
## Joshua Alabi

## Dataset

>This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment.
A number of characteristics about the patient are included in each row.

* ‘ScheduledDay’ tells us on what day the patient set up their appointment.
* ‘Neighborhood’ indicates the location of the hospital.
* ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.

## Key Finding
Appointment Day
> - Saturday has more absent patient than other weekdays.
> - People who set appointment date to weekend are likely not to attend the appointment

Gender
> - Gender does not necessary have effect on whether or not a patient will show up for an appointment

Scholarship
> - Scholarship does not necessary have effect on whether or not a patient will show up for an appointment 

Handicap
> - We **might** want to say that the higher the number of handicap, the higher the chances of missing an appointment but because those with handicap is not up to **3%** of the percentage contribution, we **cannot** conclude that Handicap has effect on whether or not a patient will show up for an appointment

SMS Received
> - We can see that from patient who received SMS,we have a higher ratio of patient who did not turn up for appointment 
> - SMS_received does not really have effect on whether or not a patient will turn up for an appointment

Age Group
> - We can see more appointment turn up from Elderly patient, maybe because at that age they are more conscious about their health
> - Teenage Age group are more likely not to show up for an appointment
> - Age has an effect on whether or not a patient is likely to show up for their medical appointment
