
Evolent Health - Project exercise for Application Development Positions 

Project Description: 
Design and implement a production ready application for maintaining contact information. Please choose the frameworks, packages and/or technologies that best suit the requirements. 
Expected functionality: 
- add a contact 
- list contacts 
- edit contact 
- delete contact 
Required Contact model: 
- First Name 
- Last Name 
- Email 
- Phone Number 
- Status (Possible values: Active/Inactive) 
Please upload to a public GitHub repository, create README instructions, host the project if feasible and send us the project link(s). Time is not a factor, we are looking for good software design practices and coding standards. 

From the below please choose the appropriate requirement for the position you are applying for. 

.NET Software Engineer (All levels) 
Design and implement a .NET REST api with appropriate data storage solution for the defined project. 

JavaScript Software Engineers (All levels) 
Design and implement a SPA for the defined project.

 
To run the application please make following changes into web.config and database.

Step 1. – Create the table on MS Sql database.

CREATE TABLE [dbo].[Contact](
	[ContactId] [int] IDENTITY(1,1) NOT NULL,
	[FirstName] [varchar](50) NULL,
	[LastName] [varchar](50) NULL,
	[Email] [varchar](50) NULL,
	[PhoneNumber] [varchar](50) NULL,
	[Status] [varchar](50) NULL,
 CONSTRAINT [PK_Contacts] PRIMARY KEY CLUSTERED 
(
	[ContactId] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON) ON [PRIMARY]
) ON [PRIMARY]


Step 2. – Change the web.config connection string.
Point to your database and refresh the solution. 


- 	Base on requirement I have created asp.net mvc. In application I have allow user to Create, Update, Delete and View List of Contacts.

- 	CURD operation base on web api call. Where on web api I have use Repository pattern.

- 	For a WebAPI we can crate seprate project and there is different hosting michinasam where we can use OWNI self hosting and other methods etc.

- 	We can add api validation base on web api header. We can pass the token and then validate that token. We can use windows authorize method.

- 	Added Unit Test Methods for CURD operation. You can automate this process. 

- 	Validation – We can use java script and class validation base on our requirement. 

- 	I can use angular js or other frame work to build this application.

- 	There is so many things I can do on this application, add bootstrap so it will work on all device. 

- 	Due to other work and busy schedule I have spends few hours only.

