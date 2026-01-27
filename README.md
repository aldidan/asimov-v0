# Specifications
- 12 DOF actuation, 6 DOF per leg
- Articulated toe
- RSU (Revolute Spherical Universal) ankle mechanism

## Left Leg

| Name         | Joint  | Min | Max | Peak Torque |
|--------------|------- |-----|-----|------------|
| L_Hip_Pitch  | Hip flexion/extension | -120° | +57° | 120 Nm |
| L_Hip_Roll   | Hip abduction/adduction | -45° | +45° | 90 Nm |
| L_Hip_Yaw    | Hip rotation | -45° | +45° | 60 Nm |
| L_Knee_Pitch | Knee flexion/extension | 0° | +86° | 75 Nm |
| L_Ankle_A    | Ankle dorsi/plantarflexion | -70° | +70° | 36 Nm |
| L_Ankle_B    | Ankle inversion/eversion | -70° | +70° | 36 Nm |

## Right Leg

| Name         | Joint | Min | Max | Peak Torque |
|--------------|-------|-----|-----|------------|
| R_Hip_Pitch  | Hip flexion/extension | -57° | +120° | 120 Nm |
| R_Hip_Roll   | Hip abduction/adduction | -45° | +45° | 90 Nm |
| R_Hip_Yaw    | Hip rotation | -45° | +45° | 60 Nm |
| R_Knee_Pitch | Knee flexion/extension | -86° | 0° | 75 Nm |
| R_Ankle_A    | Ankle dorsi/plantarflexion | -70° | +70° | 36 Nm |
| R_Ankle_B    | Ankle inversion/eversion | -70° | +70° | 36 Nm |

## Motors

- Motors from [Encos](encos.cn)

| Joint | Model |
|-------|-------|
| Pitch      | EC-A6416-P2-25   |
| Roll       | EC-A5013-H17-100 |
| Yaw        | EC-A3814-H14-107 |
| Knee_Pitch | EC-A4315-P2-36   |
| Ankle_A    | EC-A4310-P2-36   |
| Ankle_B    | EC-A4310-P2-36   |
