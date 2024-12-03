# STM_RTOS
Code:

void StartREDLED(void const * argument)
{
  for(;;)
  {
	  HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_2);
      osDelay(300);
  }
}

void StartWHITELED(void const * argument)
{
  for(;;)
  {
	  HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_3);
      osDelay(600);
  }
}


void StartBLUELED(void const * argument)
{
  for(;;)
  {
	  HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_4);
      osDelay(900);
  }
}
