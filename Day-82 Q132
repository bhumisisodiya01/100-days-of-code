Q132: Define an enum for traffic lights (RED, YELLOW, GREEN) and print 'Stop', 'Wait', or 'Go' based on its value.

/*
Sample Test Cases:
Input 1:
GREEN
Output 1:
Go

*/

#include <stdio.h>

int main() {
    enum TrafficLight {RED, YELLOW, GREEN};
    enum TrafficLight light;
    char color[10];

    printf("Enter traffic light color (RED, YELLOW, GREEN): ");
    scanf("%s", color);

    if (strcmp(color, "RED") == 0)
        light = RED;
    else if (strcmp(color, "YELLOW") == 0)
        light = YELLOW;
    else if (strcmp(color, "GREEN") == 0)
        light = GREEN;
    else {
        printf("Invalid input");
        return 1;
    }

    switch(light) {
        case RED: printf("Stop"); break;
        case YELLOW: printf("Wait"); break;
        case GREEN: printf("Go"); break;
    }

    return 0;
}
