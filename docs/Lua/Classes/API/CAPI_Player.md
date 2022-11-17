# Player

A player is a [Pawn](CAPI_Pawn.md).

Most of these functions require the playerID as the first parameter.
You can retrieve it using `GetLocalPlayerId()`
.

---

## Functions

### `AddArmor(...)`

### `AddBoolFact(...)`

### `AddPlayerMoney(...)`

### `AddReinforcementTokens(...)`

### `AddWeaponAttachment(...)`

### `AdjustBinocularZoomNow(...)`

### `AdjustCameraZoomNow(...)`

### `AirStrikeActivate(...)`

### `AirStrikeAddTokens(...)`

### `AirStrikeEnableCharge(...)`

### `ApplyDisplacement(...)`

### `ApplySlidingSpeed(...)`

### `AttachPlayer(...)`

### `AttachToGrappleAnchor(...)`

### `BlendAndRestoreFOV(...)`

### `CameraShakeAndGamePadRumble(...)`

### `ChangeGrappleArchetype(...)`

### `ClearAllWeaponAttachments(...)`

### `CompleteRaceGame(...)`

### `DeleteInventory(...)`

### `DetachPlayer(...)`

### `DrawArrow(...)`

### `DrawGadget(...)`

### `DropHealingInteractionPriority(...)`

### `EnableAnimalLooting(...)`

### `EnablePlantLooting(...)`

### `FillAmmoForAmmoType(...)`

### `FinishAnimationCycle(...)`

### `FishingForceBite(...)`

### `FishingForceLineBreak(...)`

### `ForceSetPlayerInCapture(...)`

### `ForceSetPlayerInCapturedOnChair(...)`

### `ForceSetPlayerInCaptureState(...)`

### `ForceSetPlayerInGround(...)`

### `ForceSetPlayerInRidingEntity(...)`

### `ForceSetPlayerInVehicle(...)`

### `GetBeautifierFirstMaxAngleLimits(...)`

### `GetBeautifierFirstMinAngleLimits(...)`

### `GetCurrentCyclesNumber(...)`

### `GetCurrentInventoryKey(...)`

### `GetCurrentRegion(...)`

### `GetCurrentRegionFaction(...)`

### `GetDesiredPlayerLookAngles(...)`

### `GetFlashlightArchetype(...)`

### `GetHighestPriorityInteraction(...)`

### `GetMovementSensitivity(...)`

### `GetPlayerAmmoIsEmpty(...)`

### `GetPlayerFOV(playerID)`

Returns the player's current field of view.

### `GetPlayerLookAngles(...)`

### `GetPlayerMedPackCount(...)`

### `GetPlayerMoney(...)`

### `GetPlayerNearFOV(...)`

### `GetQuickLaunchPlayerIdRef(...)`

### `GetWorldSpeed(...)`

### `GiveAmmoClipsToPlayer(...)`

### `GiveAmmoToPlayer(...)`

### `GivePlayerOutpostXPBonus(...)`

### `GivePlayerReward(...)`

### `GivePlayerXP(...)`

### `HuntingVisionStart(...)`

### `HuntingVisionStop(...)`

### `IsBeautifierFirstYawLimited(...)`

### `IsInAir(...)`

### `IsPlayerInGodMode()`

Returns true if the player is in god mode.

### `IsRadioTowerSequenceActive(...)`

### `IsSignalPressed(...)`

### `IsTrialPlayer(...)`

### `IsUsingLadder(...)`

### `LockInputPriority(...)`

### `LockInputPriorityByStringID(...)`

### `LockPlayerActionMap(...)`

### `ModifyModelTypeOfLocalPlayer(...)`

### `PopPlayerActionMap(...)`

### `PushPlayerActionMap(...)`

### `ReleaseInputPriority(...)`

### `ReleaseInputPriorityByStringID(...)`

### `RemoveAllSpawnedGadgets(...)`

### `RemoveDeviceToTrack(...)`

### `RemovePlayerActionMap(...)`

### `ResetHudReticleAlpha(...)`

### `ResetInputs(...)`

### `RestoreDefaultGrappleArchetype(...)`

### `SafeHouseAlarmDisabledFeedback(...)`

### `SelectThrowGadget(...)`

### `SetAbilityUpgradable(...)`

### `SetAlwaysSliding(...)`

### `SetCanCatchOnFire(...)`

### `SetCanGainXP(...)`

### `SetCanSprint(playerID, state)`

Sets whether the player is allowed to sprint.

### `SetCloseUpCamera(...)`

### `SetCurrentSPActivity(...)`

### `SetDivingPostFXAllowed(...)`

### `SetEffectiveCameraPositionOffset(...)`

### `SetEnableVehicleRadios(...)`

### `SetExtremeZoomCamera(...)`

### `SetFlashlightArchetype(...)`

### `SetFlashlightEnable(playerID, enabled)`

Enables or disables the flashlight.

### `SetFlashlightEnableOnJIP(...)`

### `SetHighAltitude(...)`

### `SetHudReticleAlpha(...)`

### `SetIgnorePlayerSignal(...)`

### `SetInExoticMinigame(...)`

### `SetIronSight(...)`

### `SetJumping(playerID, state)`

Jumps if the player is on the ground.

### `SetLandingDamageEnabled(playerID, enabled)`

Enables or disables fall damage.

### `SetLockRadios(...)`

### `SetMovementSensitivity(playerID, sensitivity)`

Sets the player's movement sensitivity.

### `SetOxygenLevel(...)`

### `SetPlayerActionMap(...)`

### `SetPlayerAimAngles(...)`

### `SetPlayerAimAnglesFromAngles(...)`

### `SetPlayerFOV(...)`

### `SetPlayerLookAngles(...)`

### `SetPlayerLookAnglesFromAngles(...)`

### `SetPlayerMoney(playerID, ammount)`

Sets the player's money to the specified amount.

### `SetPlayerNearFOV(...)`

### `SetPlayerPadRumble(...)`

### `SetPlayerTriggerRumble(...)`

### `SetPositionOnLadder(...)`

### `SetPostFXIntensity(...)`

### `SetPropagandaEnabled(...)`

### `SetQuickLaunchPlayerIdRef(...)`

### `SetRadioTrackOnPlayerVehicle(...)`

### `SetSprinting(playerID, state)`

Sets whether the player is sprinting.

### `SetStalkMode(...)`

### `SetSwimLookPitchLimits(...)`

### `SetWaterDivingEnable(...)`

### `SetWorldSpeed(...)`

### `StartPlayAnim(...)`

### `StartPostFX(...)`

### `StopPlayAnim(...)`

### `StopPostFX(...)`

### `SwitchCamera(...)`

### `SwitchInventory(...)`

### `SwitchPlayerPawn(...)`

### `TakeCameraPicture(...)`

### `TeleportPlayerOnLadder(...)`

### `UnlockPlayerActionMap(...)`

### `UnsetCurrentSPActivity(...)`

### `UpdateDeviceToTrack(...)`

### `UpdateMovement(...)`

### `UpdatePlayerInCapture(...)`

### `UpdatePlayerInCaptureState(...)`

### `UpdateRaceGameTimer(...)`

### `VerifyInputPriority(...)`

### `VerifyInputPriorityByStringID(...)`

### `VisionModeStartBliss(playerID, duration, false)`

Starts the bliss vision mode for the specified player.

### `VisionModeStartCustomIntoxication(...)`

### `VisionModeStartDrunk(playerID, duration, false)`

Starts the drunk vision mode for the specified player.

### `VisionModeStartHigh(playerID, duration, false)`

Starts the high vision mode for the specified player.

### `VisionModeStartScopolamineHeavy(...)`

### `VisionModeStartScopolamineLow(...)`

### `VisionModeStartScopolamineMedium(...)`

### `VisionModeStartSuppression(...)`

### `VisionModeStop(playerID)`

Stops the current vision mode for the specified player.

### `WithdrawPlayerMoney(...)`
