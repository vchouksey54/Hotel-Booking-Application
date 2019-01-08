# Hotel-Booking-Application
Hotel Booking Application
SQL queries below


CREATE TABLE [dbo].[tblCityMaster]
(
	[Id] INT NOT NULL PRIMARY KEY IDENTITY, 
    [NameOfCity] VARCHAR(120) NULL, 
    [State] VARCHAR(120) NULL
)

Id	NameOfCity	State
1	Mumbai	Maha Rashtra
2	Pune	Maha Rashtra
3	Indore	Madhya Pradesh
4	Bhopal	Madhya Pradesh


CREATE TABLE [dbo].[tblHotelList] (
    [Id]             INT           IDENTITY (1, 1) NOT NULL,
    [HotelName]      VARCHAR (120) NULL,
    [HotelRating]    VARCHAR (120) NULL,
    [HotelImage]     IMAGE         NULL,
    [City]           VARCHAR (120) NULL,
    [address]        VARCHAR (255) NULL,
    [chargePerNight] VARCHAR (255) NULL,
    PRIMARY KEY CLUSTERED ([Id] ASC)
);



Id	HotelName	HotelRating	HotelImage	City
1	Hotel_mum_1	3	NULL	Mumbai
2	Hotel_mum_2	4	NULL	Mumbai
3	Hotel_pune_1	3	NULL	Pune
4	Hotel_pune_2	4	NULL	Pune
5	Hotel_indb_1	3	NULL	Indore
6	Hotel_indb_2	4	NULL	Indore
7	Hotel_bpl_1	3	NULL	Bhopal
8	Hotel_bpl_2	4	NULL	Bhopal




