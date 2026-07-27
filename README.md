India-Open-World
Source/IndiaOpenWorld
PlayerCharacter.cpp
// India Open World
// Player Character System

#include "PlayerCharacter.h"

APlayerCharacter::APlayerCharacter()
{
    PrimaryActorTick.bCanEverTick = true;

    PlayerHealth = 100;
    PlayerMoney = 5000;
}

void APlayerCharacter::BeginPlay()
{
    Super::BeginPlay();
}

void APlayerCharacter::Tick(float DeltaTime)
{
    Super::Tick(DeltaTime);
}

void APlayerCharacter::Run()
{
    UE_LOG(LogTemp, Warning, TEXT("Player Running"));
}

void APlayerCharacter::JumpAction()
{
    UE_LOG(LogTemp, Warning, TEXT("Player Jump"));
}

void APlayerCharacter::EnterVehicle()
{
    UE_LOG(LogTemp, Warning, TEXT("Entered Vehicle"));
}
