## Schema

### Optional

- `certificate_authority_arn` (String)
- `certificate_body` (String)
- `certificate_chain` (String)
- `domain_name` (String)
- `options` (Block List, Max: 1) (see [below for nested schema](#nestedblock--options))
- `private_key` (String, Sensitive)
- `subject_alternative_names` (Set of String)
- `tags` (Map of String)
- `tags_all` (Map of String)
- `validation_method` (String)

### Read-Only

- `arn` (String)
- `domain_validation_options` (Set of Object) (see [below for nested schema](#nested-schema-for-domain_validation_options))
- `id` (String) The ID of this resource.
- `status` (String)
- `validation_emails` (List of String)

### Nested Schema for `options`

Optional:

- `certificate_transparency_logging_preference` (String)


### Nested Schema for `domain_validation_options`

Read-Only:

- `domain_name` (String)
- `resource_record_name` (String)
- `resource_record_type` (String)
- `resource_record_value` (String)
