### Mr Fix-It
#### A repair technician job service.




COMPLETED:
* Users can register and log on
* Users may sign up to be "workers" on the site.
* New jobs may be added to the jobs list.
* A job can be assigned to a worker.
* A worker may take on mulitple jobs from the Worker Dashboard.
* Make *claiming* a job an **AJAX** action.
* A Worker may designate which jobs are active.
* A worker may designate which jobs have been completed.
* Users can delete jobs.

IN PROGRESS
* A worker may designate one **active** job at a time. **AJAX**
* Workers may mark jobs complete, and select a new active job. **AJAX**

NEXT UP
...

## Setup/Installation Requirements

Clone this repository: https://github.com/albelka/Mr-FIxit
 and open it in Visual Studio.

* _In SSMS :_
```
open dbMrFixit.sql
add these lines to the top of the query
CREATE DATABASE MrFixIt
GO 
```

In VisualStudio right click on MrFixIt in the Solution Explorer and select **Build**

Then in the command prompt write:
```
> dotnet ef database update
```

Now run Mr Fix-It in Visual Studio to view it in any modern browser.

## Technologies Used
* C#
* VisualStudio
* ASP.Net
* Entity Framework
* Identity Framework Core
* AJAX
* JQuery

#### Contribution by Anne Belka