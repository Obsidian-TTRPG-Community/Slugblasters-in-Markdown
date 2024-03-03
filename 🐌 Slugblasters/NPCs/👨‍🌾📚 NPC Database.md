---

database-plugin: basic

---

```yaml:dbfolder
name: NPC Database
description: 
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 1
    isHidden: false
    sortIndex: 2
    isSorted: true
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  NoteIcon:
    input: select
    accessorKey: NoteIcon
    key: NoteIcon
    id: NoteIcon
    label: NoteIcon
    position: 6
    skipPersist: false
    isHidden: true
    sortIndex: -1
    options:
      - { label: "NPC", value: "NPC", color: "hsl(350, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Art:
    input: text
    accessorKey: Art
    key: Art
    id: Art
    label: Art
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Pronouns:
    input: select
    accessorKey: Pronouns
    key: Pronouns
    id: Pronouns
    label: Pronouns
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "He/Him", value: "He/Him", color: "hsl(278, 95%, 90%)"}
      - { label: "She/Her", value: "She/Her", color: "hsl(217, 95%, 90%)"}
      - { label: "N/A", value: "N/A", color: "hsl(96, 95%, 90%)"}
      - { label: "They/Them", value: "They/Them", color: "hsl(358, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Notes:
    input: text
    accessorKey: Notes
    key: Notes
    id: Notes
    label: Notes
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 175
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Affiliation:
    input: select
    accessorKey: Affiliation
    key: Affiliation
    id: Affliliation
    label: Affiliation
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: 0
    width: 141
    isSorted: true
    isSortedDesc: false
    options:
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/BRB.md|BRB]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/BRB.md|BRB]]", color: "hsl(280,17%,48%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Jet Collective.md|Jet Collective]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Jet Collective.md|Jet Collective]]", color: "hsl(154,24%,39%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Null Range.md|Null Range]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Null Range.md|Null Range]]", color: "hsl(334,69%,29%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Lazy Bunny.md|Lazy Bunny]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Lazy Bunny.md|Lazy Bunny]]", color: "hsl(192,51%,41%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Wicks.md|The Wicks]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Wicks.md|The Wicks]]", color: "hsl(41,43%,37%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Arborists.md|The Arborists]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Arborists.md|The Arborists]]", color: "hsl(310, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/DARA.md|DARA]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/DARA.md|DARA]]", color: "hsl(329, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Shimmer.md|Shimmer]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Shimmer.md|Shimmer]]", color: "hsl(14, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Old Guard.md|The Old Guard]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Old Guard.md|The Old Guard]]", color: "hsl(75, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Doorways.md|Doorways]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Doorways.md|Doorways]]", color: "hsl(214, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Scram Cat.md|Scram Cat]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Scram Cat.md|Scram Cat]]", color: "hsl(338, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Miper.md|Miper]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Miper.md|Miper]]", color: "hsl(308, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Hardecker.md|Hardecker]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Hardecker.md|Hardecker]]", color: "hsl(138, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Wilkie's.md|Wilkie's]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/Wilkie's.md|Wilkie's]]", color: "hsl(327, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/FUST.md|FUST]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/FUST.md|FUST]]", color: "hsl(352, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Thrashers.md|The Thrashers]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Thrashers.md|The Thrashers]]", color: "hsl(249, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Heads.md|The Heads]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Heads.md|The Heads]]", color: "hsl(249, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Mavens.md|The Mavens]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Mavens.md|The Mavens]]", color: "hsl(261, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Freaks.md|The Freaks]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Freaks.md|The Freaks]]", color: "hsl(50, 95%, 90%)"}
      - { label: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Normies.md|The Normies]]", value: "[[20 🌟 GM Campaigns/🐌 Slugblaster/Groups/The Normies.md|The Normies]]", color: "hsl(116, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: true
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: false
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
  row_templates_folder: z_Templates
  current_row_template: 90 🧩 Templates/NPC.md
  pagination_size: 55
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```