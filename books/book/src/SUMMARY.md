# Radix Engine

[Introduction](README.md)

# Architecture

- [Layered Architecture](architecture/layers.md)
- [Application Layer](architecture/application/README.md)
  - [Object](architecture/application/object/README.md)
    - [BlueprintId](architecture/application/object/blueprint_id.md)
    - [Outer Object](architecture/application/object/inner_outer_objects.md)
    - [Features](architecture/application/object/features.md)
    - [Generic Substitutions](architecture/application/object/generic_substitutions.md)
    - [Object Modules](architecture/application/object/object_modules.md)
  - [Blueprint](architecture/application/blueprint/README.md)
    - [Inner and Outer Blueprints](architecture/application/blueprint/inner_outer.md)
    - [Transience](architecture/application/blueprint/transience.md)
    - [Features](architecture/application/blueprint/features.md)
    - [Generics](architecture/application/blueprint/generics.md)
    - [Fields](architecture/application/blueprint/fields.md)
    - [Collections](architecture/application/blueprint/collections.md)
    - [Events](architecture/application/blueprint/events.md)
    - [Functions/Methods](architecture/application/blueprint/functions.md)
    - [Hooks](architecture/application/blueprint/hooks.md)
    - [Types](architecture/application/blueprint/types.md)
    - [Blueprint Modules](architecture/application/blueprint/blueprint_modules.md)
  - [Type Checking](architecture/application/type_checking/README.md)
- [VM Layer](architecture/vm/README.md)
- [System Layer](architecture/system/README.md)
  - [System Modules](architecture/system/system_modules.md)
- [Kernel Layer](architecture/kernel/README.md)
- [Database Layer](architecture/database/README.md)

# Execution

- [Transaction Lifecycle](execution/transaction_lifecycle/README.md)
  - [Bootup](execution/transaction_lifecycle/bootup.md)
  - [Runtime](execution/transaction_lifecycle/runtime.md)
  - [Shutdown](execution/transaction_lifecycle/shutdown.md)
- [Application Environment](execution/environment/README.md)
  - [Objects](execution/environment/object_lifecycle.md)
  - [Invocations](execution/environment/invocations.md)
  - [State Reads/Writes](execution/environment/state_reads_writes.md)

# Native Systems

- [Transaction Processor](native/transaction_processor/README.md)
  - [Transaction Processor Blueprint](native/transaction_processor/blueprint.md)
- [Resources](native/resources/README.md)
- [Auth](native/auth/README.md)
  - [Auth Blueprint Module](native/auth/blueprint_module.md)
  - [Role Assignment Object Module](native/auth/role_assignment.md)
  - [Auth Zone Blueprint](native/auth/authzone.md)
  - [Auth System Module](native/auth/system_module.md)
- [Costing/Limits](native/costing_limits/README.md)
- [Royalties](native/royalties/README.md)
  - [Package Royalties Blueprint Module](native/royalties/package_royalties.md)
  - [Component Royalties Object Module](native/royalties/component_royalties.md)
- [Metadata](native/metadata/README.md)
  - [Metadata Object Module](native/metadata/object_module.md)

# Protocol
- [Genesis Bootstrap](protocol/genesis_bootstrap.md)
- [Protocol Updates](protocol/protocol_updates.md)
 