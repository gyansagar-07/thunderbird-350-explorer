# Thunderbird 350 Twin Spark — mechanical blueprint baseline

> **Scope:** standard carburetted Royal Enfield Thunderbird 350 Twin Spark, user-identified as a 2017 motorcycle. The 350X is explicitly excluded. The exact year/variant still needs documentary confirmation before parts are marked compatible.

## Accuracy rules
- This is a coverage checklist and data schema, not a claim that every subcomponent has already been verified.
- Confirm each part against the applicable Thunderbird Twinspark catalogue and service documentation, including later service bulletins.
- Keep unknown part numbers, torque values, clearances, fluid quantities, and prices blank until sourced.
- Marketplace search matches are leads only, not proof of compatibility.
- A symptom never proves a part has failed. Diagnose with discriminating checks before recommending replacement.
- Brake failure, fuel leaks, tyre damage, severe metallic engine noise, and dangerous electrical faults require clear stop-use guidance.

## System coverage checklist
### Frame and chassis
- main frame
- steering head
- swingarm
- engine mounts
- stands
- brackets
- fasteners

### Engine top end
- cylinder head
- head cover
- valve train
- rockers
- valves
- springs
- cam drive
- cylinder
- piston
- rings
- gaskets
- seals
- fasteners

### Engine bottom end
- crankcase halves
- crankshaft
- connecting rod
- main bearings
- oil passages
- oil pump
- sump / strainer components as applicable
- seals
- gaskets
- fasteners

### Twin Spark ignition
- two spark plugs
- plug caps
- ignition coils / coil arrangement per variant
- HT leads
- ignition pickup / sensor as fitted
- ignition control and wiring

### Fuel and intake
- fuel tank
- cap
- tap / supply components as fitted
- fuel hose
- carburettor
- choke / enrichment mechanism
- throttle cable
- intake manifold
- airbox
- filter element
- resonator / intake ducts as fitted

### Lubrication
- oil pump
- oil galleries
- strainer / filter components as fitted
- oil lines if fitted
- drain plug
- seals
- gaskets

### Clutch and gearbox
- clutch lever and cable
- clutch release mechanism
- clutch basket
- friction plates
- steel plates
- springs
- gearbox shafts
- gears
- selector mechanism
- bearings
- seals

### Final drive
- front sprocket
- drive chain
- rear sprocket
- chain adjusters
- guards
- fasteners

### Front brake
- lever
- master cylinder / cable mechanism according to variant
- hose / cable
- caliper if fitted
- pads or shoes as fitted
- disc or drum as fitted
- mounts
- fasteners

### Rear brake
- pedal
- pivot and return spring
- operating rod / cable / linkage as fitted
- equaliser / adjuster as fitted
- cam / actuator
- shoes and springs or disc components according to exact variant
- drum / rotor
- wheel interface
- fasteners

### Wheels and tyres
- front wheel
- rear wheel
- rim
- spokes or wheel construction as fitted
- hubs
- bearings
- axles
- spacers
- valves
- tyres

### Suspension and steering
- fork legs
- fork internals
- seals
- triple clamps
- steering bearings
- handlebar
- rear shock absorbers
- swingarm bushes
- mounting hardware

### Electrical, starting and charging
- battery
- starter motor
- starter relay
- charging stator / alternator
- regulator rectifier
- fuses
- wiring harness
- switches
- connectors
- lights
- indicators
- horn
- instrument cluster

### Bodywork and rider controls
- tank
- seat
- side panels
- mudguards
- headlamp housing
- tail lamp
- mirrors
- grips
- levers
- footrests
- pedals
- cables
- instrument pods
- mounting fasteners

### Exhaust
- header pipe
- exhaust gasket
- silencer
- mounts
- heat shields if fitted
- fasteners

## Component data record
Each component record should include:
- Stable component ID and exact catalogue name
- Parent system and neighbouring / connected components
- Part number and fitment status, with source
- Function in plain language
- Common symptoms and differential causes
- Safe inspection steps and tests
- Repair / adjustment / cleaning options
- Conditions that justify replacement
- Safety level and mechanic escalation
- 3D scene node / mesh mapping
- Source references and confidence status

## 3D acceptance criteria
- Use a named-mesh GLB/glTF asset so clicks map to stable component IDs.
- Orbit, zoom, pan, focus-camera, isolate/hide, and exploded-view controls are required.
- Mechanism animation must reflect the actual mechanism; do not simulate a confirmed fault without evidence.
- A Thunderbird 350X asset is not acceptable as the target model. Validate the standard Thunderbird 350 Twin Spark exterior and mechanical configuration first.
- An exterior-only model must never be represented as a complete mechanical digital twin.

## Machine-readable baseline
See `../data/bike-blueprint.json` for the structured initial system list and diagnostic / 3D requirements.
