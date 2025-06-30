# Whileloop
While looping project
#include <stdio.h>

int main() {
  int i = 1;
  while (i <= 5) {
    printf("%d ", i);
    i++; // Increment i to avoid infinite loop
  }
  return 0;
}
