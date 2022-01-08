# quartz-email-scheduler
Springboot with quartz to schedule emails.
How to run this project:-
1. Run as java application using main class.
2. For SMTP configuration can you visit below link for fake smtp just for testing purpose.
 https://ethereal.email/
3. This scheduler basically schedules a job to send an email.
4. You need to hit below POST request on local:-
  http://localhost:9999/scheduleEmail
  
  RequestBody example:-
  
  {
	"email":"test@gmail.com",
	"subject":"test",
	"body":"testing",
	"dateTime":"2022-01-08T07:02",
	"timeZone":"Asia/Kolkata"
}
  
