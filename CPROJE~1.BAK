#include<stdio.h>
#include<conio.h>
#include<string.h>
void booktickets();
void search();
void viewall();
void viewbookings();
void exit();
void pari();
void avengers();
void raid();
void two();
void pacific();
void blackpanther();
void hichki();
void october();
void allfun();
void baaghi();
void tomb();
int main()
{
    int choice;
    clrscr();

    do
    {
 printf("\t\t\t*****************************\n");
 printf("\t\t\tMovie Ticket Booking System\n");
 printf("\t\t\t*****************************\n\n\n");
 printf("\t\t\tPRESS <1> SEARCH MOVIES\n");
 printf("\t\t\tPRESS <2> VIEW ALL MOVIES\n");
 printf("\t\t\tPRESS <3> BOOK THE TICKETS\n");
 printf("\t\t\tPRESS <4> VIEW ALL BOOKINGS\n");
 printf("\t\t\tPRESS <0> EXIT\n");
 printf("enter your choice:");
 scanf("%d",&choice);
 switch(choice)
 {
   case 1:
   search();
   break;

   case 2:
   viewall();
   break;

   case 3:
   booktickets();
   break;

   case 4:
   viewbookings();
   break;

   case 0:
   exit();
   break;

   default:
   printf("invalid");
}
getch();
}while(choice!=0);
return 0;
}
void exit()
{
    printf("THANK YOU FOR USING OUR SYSTEM");
}
void booktickets()
 {
	int moviename,enter;
	char section[50];
   FILE *ufp;
    char period[50];
    int seats,cost;
    char name[50];
    char mobile[50];
    char kal[50];
    char movie[50];
    label:
    clrscr();
	viewall();
	printf("enter code of the movie from the list above:\n");
	scanf("%d",&moviename);
	printf("\nenter name of the movie:\n");
	scanf("%s",&movie);

	switch(moviename)
	{
	case 1:
	pari();
	break;

	case 2:
	avengers();
	break;

	case 3:
	raid();
	break;

	case 4:
	blackpanther();
	break;

	case 5:
	october();
	break;

	case 6:
	hichki();
	break;

	case 7:
	pacific();
	break;

	case 8:
	two();
	break;

	case 9:
	baaghi();
	break;

	case 10:
	tomb();
	break;
	}
	printf("\nEnter the section (Premium,Silver,Regular)\n");
	scanf("%s",section);
	printf("Enter the period(Morning,Afternoon,Night)\n");
	scanf("%s",period);
	printf("Enter number of seats\n");
	scanf("%d",&seats);
	if((strcmp(section,"premium")==0) && (strcmp(period,"morning")==0))
	{
	printf("cost of each seats is 250\n");
	cost=seats*250;
	printf("Total cost is %d\n",cost);
	}
	else if((strcmp(section,"premium")==0) && (strcmp(period,"afternoon")==0))
	{
	printf("cost of each seats is 350\n");
	cost=seats*350;
	printf("Total cost is %d\n",cost);
	}
	else if((strcmp(section,"premium")==0) && (strcmp(period,"night")==0))
	{
	printf("cost of each seats is 450\n");
	cost=seats*450;
	printf("Total cost is %d\n",cost);
	}
	else if((strcmp(section,"silver")==0) && (strcmp(period,"morning")==0))
	{
	printf("cost of each seats is 150\n");
	cost=seats*150;
	printf("Total cost is %d\n",cost);
	}
	else if((strcmp(section,"silver")==0) && (strcmp(period,"afternoon")==0))
	{
	printf("cost of each seats is 250\n");
	cost=seats*250;
	printf("Total cost is %d\n",cost);
	}
	else if((strcmp(section,"silver")==0) && (strcmp(period,"night")==0))
	{
	printf("cost of each seats is 350\n");
	cost=seats*350;
	printf("Total cost is %d\n",cost);
	}
	else if((strcmp(section,"regular")==0) && (strcmp(period,"morning")==0))
	{
	printf("cost of each seats is 100\n");
	cost=seats*100;
	printf("Total cost is %d\n",cost);
	}
	else if((strcmp(section,"regular")==0) && (strcmp(period,"afternoon")==0))
	{
	printf("cost of each seats is 200\n");
	cost=seats*200;
	printf("Total cost is %d\n",cost);
	}
	else if((strcmp(section,"regular")==0) && (strcmp(period,"night")==0))
	{
	printf("cost of each seats is 250\n");
	cost=seats*250;
	printf("Total cost is %d\n",cost);
	}
	else
	{
	printf("UNVALID\n");
	}
    printf("\nDO YOU WANT TO BOOK THE TICKET FOR THIS MOVIE\nEnter <1> for YES and <2> for NO:");
	scanf("%d",&enter);
	switch(enter)
	{
    case 2:
	allfun();
	break;
    case 1:
	printf("*****************************\n");
	printf("FILL YOUR DETAILS\n");
	printf("*****************************\n");

    printf("What time show do you want: ");
    scanf("%s",&kal);
    printf("Enter you name: ");
    scanf("%s",&name);
    printf("Enter your mobile number: ");
    scanf("%s",&mobile);
    printf("\n\n\t\t******ENJOY THE MOVIE******\n");
    printf("\t\tNAME:%s\n",name);
    printf("\t\tMOBILE NUMBER:%s\n",mobile);
    printf("\t\tNAME OF THE MOVIE:%s\n",movie);
    printf("\t\tNUMBER OF SEATS:%d\n",seats);
    printf("\t\tTIMING FOR THE SHOW:%s\n",kal);
    printf("\t\tSECTION OF SEAT:%s\n",section);
    printf("\t\tTOTAL COST:%d\n",cost);

    printf("\tYOU HAVE SUCCESFULLY BOOKED YOUR TICKET FOR THE MOVIE %s\n",strupr(movie));
    }
    ufp=fopen("oldTransection.txt","a");
	if(ufp == NULL)
	{
		printf("FIle not Found");
	}
	else
	{
		fprintf(ufp,"NAME:%s\nMOBILE NUMBER:%s\nMOVIE NAME:%s\nSEATS:%d\nTIMING:%s\nSECTION OF SEAT:%s\nTOTAL COST:%d \n",name,mobile,movie,seats,kal,section,cost);
		printf("\tRecord insert Sucessfull to the old record file");
	}
		printf("\n\n");
	fclose(ufp);
}



void allfun()
{
main();
}
void search()
{
	int sear;
	clrscr();
	printf("\tPRESS<1> FOR PARI\n");
	printf("\tPRESS<2> FOR AVENGERS\n");
	printf("\tPRESS<3> FOR RAID\n");
	printf("\tPRESS<4> FOR BLACK PANTHER\n");
	printf("\tPRESS<5> FOR OCTOBER\n");
	printf("\tPRESS<6> FOR HICHKI\n");
	printf("\tPRESS<7> FOR PACIFIC RIM UPRISING\n");
	printf("\tPRESS<8> FOR 2.0\n");
	printf("\tPRESS<9> FOR BAAGHI 2\n");
	printf("\tPRESS<10> FOR TOMB RAIDER\n");
	printf("SEARCH:");
	scanf("%d",&sear);
	switch(sear)
	{
	case 1:
	pari();
	break;

	case 2:
	avengers();
	break;

	case 3:
	raid();
	break;

	case 4:
	blackpanther();
	break;

	case 5:
	october();
	break;

	case 6:
	hichki();
	break;

	case 7:
	pacific();
	break;

	case 8:
	two();
	break;

	case 9:
	baaghi();
	break;

	case 10:
	tomb();
	break;
	}
}
       void hichki()
{
	printf("\nHichki (Morning Shows)\n");
	printf("Prices= Premium=250	Silver=200	 Regular=100\n");
	printf("Timings=9:00 to 11:00\n");

	printf("\nHichki (Afternoon & Evening Shows)\n");
	printf("Prices= Premium=350	 Silver=250	Regular=150\n");
	printf("Timings=5:00 to 8:00\n");


}

       void october()
{
	printf("\nOctober (Morning Shows)\n");
	printf("Prices= Premium=250	Silver=200	 Regular=100\n");
	printf("Timings=2:00 to 5:00\n");

	printf("\nOctober (Afternoon & Evening Shows)\n");
	printf("Prices= Premium=350	 Silver=250	Regular=150\n");
	printf("Timings=5:00 to 8:00\n");

	printf("\nOctober(Night Shows)\n");
	printf("Prices= Premium=450	Silver=350	 Regular=250\n");
	printf("Timings= 11:00 to 2:00\n");
}

       void pari()
{
	printf("\nPari (Morning Shows)\n");
	printf("Prices= Premium=250	Silver=200	 Regular=100\n");
	printf("Timings=9:00 to 11:00\n");

	printf("\nPari(Night Shows)\n");
	printf("Prices= Premium=450	Silver=350	 Regular=250\n");
	printf("Timings=5:00 to 8:00\n");
}
void avengers()
{

	printf("\Avengers (Morning Shows)\n");
	printf("Prices= Premium=250	 Silver=200	 Regular=100\n");
	printf("Timings=Sorry! No shows available\n");

	printf("\nAvengers (Afternoon And Evening Shows)\n");
	printf("Prices= Premium=350	 Silver=250	 Regular=150\n");
	printf("Timings=11:00 to 2:00\n");
	printf("Timings=2:00 to 5:00\n");

	printf("\nAvengers (Night Shows)\n");
	printf("Prices= Premium=450	 Silver=350	 Regular=250\n");
	printf("Timings=8:00 to 11:00\n 11:00 to 2:00\n");
}

       void blackpanther()
{
	printf("\nBlack Panther (Morning Shows)\n");
	printf("Prices= Premium=250	Silver=200	 Regular=100\n");
	printf("Timings=9:00 to 11:00\n");

	printf("\nBlack Panther (Afternoon & Evening Shows)\n");
	printf("Prices= Premium=350	 Silver=250	Regular=150\n");
	printf("Timings=11:00 to 2:00\n");

	printf("\nBlack panther (Night Shows)\n");
	printf("Prices= Premium=450	Silver=350	 Regular=250\n");
	printf("Timings=8:00 to 11:00\n");
}
void raid()
{

	printf("\nRaid (Morning Shows)\n");
	printf("Prices= Premium=250	 Silver=200	 Regular=100\n");
	printf("Timings=Sorry! No shows available\n");

	printf("\nRaid(Afternoon Shows & Evening)\n");
	printf("Prices= Premium=350	 Silver=250	 Regular=150\n");
	printf("Timings=2:00 to 5:00\n");
	printf("Timings= 5:00 to 8:00\n");


	printf("\n\nRaid (Night Shows)\n");
	printf("Prices= Premium=450	 Silver=350	 Regular=250\n");
	printf("Timings= 11:00 to 2:00\n");
}

       void tomb()
{
	printf("\nTomb (Morning Shows)\n");
	printf("Prices= Premium=250	Silver=200	 Regular=100\n");
	printf("Timings=9:00 to 11:00\n");

	printf("\nTomb (Afternoon & Evening Shows)\n");
	printf("Prices= Premium=350	 Silver=250	Regular=150\n");
	printf("Timings=11:00 to 2:00\n");

	printf("\n Tomb (Night Shows)\n");
	printf("Prices= Premium=450	Silver=350	 Regular=250\n");
	printf("Timings=8:00 to 11:00\n");
}
void baaghi()
{

	printf("\nBaaghi 2 (Morning Shows)\n");
	printf("Prices= Premium=250	 Silver=200	 Regular=100\n");
	printf("Timings=Sorry! No shows available\n");

	printf("\nBaaghi 2 (Afternoon Shows & Evening shows)\n");
	printf("Prices= Premium=350	 Silver=250	 Regular=150\n");
	printf("Timings=2:00 to 5:00\n");
	printf("Timings=5:00 to 8:00\n");


	printf("\nBaaghi 2 (Night Shows)\n");
	printf("Prices= Premium=450	 Silver=350	 Regular=250\n");
	printf("Timings=11:00 to 2:00\n");
}

       void pacific()
{
	printf("\nPacific Rim Uprising (Morning Shows)\n");
	printf("Prices= Premium=250	Silver=200	 Regular=100\n");
	printf("Timings=9:00 to 11:00\n");

	printf("\nPacific Rim Uprising (Afternoon & Evening Shows)\n");
	printf("Prices= Premium=350	 Silver=250	Regular=150\n");
	printf("Timings=11:00 to 2:00\n");

	printf("\nPacific Rim Uprising (Night Shows)\n");
	printf("Prices= Premium=450	Silver=350	 Regular=250\n");
	printf("Timings=8:00 to 11:00\n");
}
void two()
{

	printf("\n2.0 (Morning Shows)\n");
	printf("Prices= Premium=250	 Silver=200	 Regular=100\n");
	printf("Timings=Sorry! No shows available\n");

	printf("\n2.0 (Afternoon And Evening Shows)\n");
	printf("Prices= Premium=350	 Silver=250	 Regular=150\n");
	printf("Timings=11:00 to 2:00\n");
	printf("Timings=2:00 to 5:00\n");


	printf("\n\n2.0 (Night Shows)\n");
	printf("Prices= Premium=450	 Silver=350	 Regular=250\n");
	printf("Timings=8:00 to 11:00\n 11:00 to 2:00\n");
}

  void viewall()
{
	printf("	LIST OF ALL MOVIES\n\n\n");
	printf("<1>	Pari\n\n");
	printf("<2>	Avengers: Infinity War\n\n");
	printf("<3>	Raid\n\n");
	printf("<4>	Black Panther\n\n");
	printf("<5>	October\n\n");
	printf("<6>	Hichki\n\n");

	printf("<7>	Pacific Rim Uprising\n\n");
	printf("<8>	2.0\n\n");
	printf("<9>	Baaghi 2\n\n");
	printf("<10> Tomb Raider\n\n");
}
void viewbookings()
{

    FILE *fp;
    char ch;
    clrscr();
     fp = fopen("oldTransection.txt","r");
	if(fp == NULL)
	{
		printf("file does not found !");


	}
	else
	{
		while( ( ch = fgetc(fp) ) != EOF )
		printf("%c",ch);

	}
	fclose(fp);
}










