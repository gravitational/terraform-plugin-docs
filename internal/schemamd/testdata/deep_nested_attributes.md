## Schema

### Required

- `level_one` (Attributes) (see [below for nested schema](#nested-schema-for-level_one))

### Read-Only

- `id` (String) Example identifier

### Nested Schema for `level_one`

Optional:

- `level_two` (Attributes) (see [below for nested schema](#nested-schema-for-level_onelevel_two))

### Nested Schema for `level_one.level_two`

Optional:

- `level_three` (Attributes) (see [below for nested schema](#nested-schema-for-level_onelevel_twolevel_three))

### Nested Schema for `level_one.level_two.level_three`

Optional:

- `level_four_primary` (Attributes) (see [below for nested schema](#nested-schema-for-level_onelevel_twolevel_threelevel_four_primary))
- `level_four_secondary` (String)

### Nested Schema for `level_one.level_two.level_three.level_four_primary`

Optional:

- `level_five` (Attributes) Parent should be level_one.level_two.level_three.level_four_primary. (see [below for nested schema](#nested-schema-for-level_onelevel_twolevel_threelevel_four_primarylevel_five))
- `level_four_primary_string` (String) Parent should be level_one.level_two.level_three.level_four_primary.

### Nested Schema for `level_one.level_two.level_three.level_four_primary.level_five`

Optional:

- `level_five_string` (String) Parent should be level_one.level_two.level_three.level_four_primary.level_five.
