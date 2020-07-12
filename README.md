# BikeRacing
A Bike race is to be organized. There will be N bikers. You are given initial Speed of the ith Biker by Hi Km/hr and the Acceleration of ith biker as Ai Km/Hr2.

The organizers want the safety of the bikers and the viewers.They monitor the Total Speed on the racing track after every Hour. A biker whose Speed is 'L' or more, is considered a Fast Biker. To Calculate the Total speed on the track- They Add the speed of each Fast biker ,at that Hour. As soon as The total speed on the track is 'M' KiloMeters per Hour or more, The safety Alarm buzzes. You need to tell what is the minimum number of Hours after which the safety alarm will buzz.

Input: The first Line contains Testcases- denoting the number of test cases. The first line of each test case contains three space-separated integers N, M and L denoting the number of bikers and speed limit of the track respectively, and A fast Biker's Minimum Speed. Each of next N lines contains two space-separated integers denoting Hi and Ai respectively.

Output: For each test case-Output a single integer denoting the minimum number of Hours after which alarm buzzes.

Constraints: 1<=T<=100 1<=N<=1e5 1 ≤ M,L ≤ 1e10 1 ≤ Hi, Ai ≤ 1e9

Explanation: Sample Input: 1 3 400 120 20 20 50 70 20 90

Sample Output: 3

Explanation: Speeds of all the Bikers at ith Minute Biker1= 20 40 60 80 100 120 Biker2= 50 120 190 260 330 Biker3= 20 110 200 290 380

Total Initial speeds = 0 (Because none of the biker's speed is fast enough) total Speed at 1st Hour= 120 total Speed at 2nd Hour= 190+200=390 total Speed at 3rd Hour= 260+290=550 Alarm will buzz at 3rd Hour.
