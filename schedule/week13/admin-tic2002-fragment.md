{% from "common/macros.njk" import embed_topic, show_as_tab, thumb, timing_badge with context %}
{% from "common/admin.njk" import show_admin_summary with context %}


{% call show_admin_summary() %}

{{ icon_project }} **Project:**
1. Submit the project {{ timing_badge("Sunday 2359") }}
{% endcall %}

#### {{ thumb(1) }} Attend the mock exam {{ timing_badge("during lecture", "secondary") }}

* This week's lecture will give a brief recap of the course and brief you about the exam.

<!-- ==================================================================================================== -->
{{ heading_project }}
<div id="project">

#### {{ thumb(1) }} Submit the project {{ timing_badge("Sunday 2359", "secondary") }}

{{ embed_topic("../../admin/index-tic2002-fragment.md#final-submission-info", "Admin " + icon_embedding + " Project → Final Submission", "week13Admin-finalSubmission", "1") }}

</div>
