{% if currentVersion == "enterprise-server@2.22" %}

{% note %}

**Note**: If you enable beta features for {% data variables.product.prodname_ghe_server %} 2.22, your instance requires additional hardware resources. Minimum requirements for an instance with beta features enabled are **bold** in the following table. For more information about the features in beta, see "[Beta features in {% data variables.product.prodname_ghe_server %} 2.22](#beta-features-in-github-enterprise-server-222)."

{% endnote %}
|
{% endif %}
| User licenses                  |                                                                                                                                  vCPUs |                                                                                                                                         Memory |                                                                                                                               Attached storage | Root storage |
|:------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------:| ----------------------------------------------------------------------------------------------------------------------------------------------:| ----------------------------------------------------------------------------------------------------------------------------------------------:| ------------:|
| Trial, demo, or 10 light users |   2{% if currentVersion == "enterprise-server@2.22" %}<br/>or [**4**](#beta-features-in-github-enterprise-server-222){% endif %} |   16 GB{% if currentVersion == "enterprise-server@2.22" %}<br/>or [**32 GB**](#beta-features-in-github-enterprise-server-222){% endif %} | 100 GB{% if currentVersion == "enterprise-server@2.22" %}<br/>or [**150 GB**](#beta-features-in-github-enterprise-server-222){% endif %} |       200 GB |
| 10 to 3,000                    |   4{% if currentVersion == "enterprise-server@2.22" %}<br/>or [**8**](#beta-features-in-github-enterprise-server-222){% endif %} |   32 GB{% if currentVersion == "enterprise-server@2.22" %}<br/>or [**48 GB**](#beta-features-in-github-enterprise-server-222){% endif %} | 250 GB{% if currentVersion == "enterprise-server@2.22" %}<br/>or [**300 GB**](#beta-features-in-github-enterprise-server-222){% endif %} |       200 GB |
| 3,000 to 5000                  |  8{% if currentVersion == "enterprise-server@2.22" %}<br/>or [**12**](#beta-features-in-github-enterprise-server-222){% endif %} |                                                                                                                                          64 GB |                                                                                                                                         500 GB |       200 GB |
| 5,000 to 8000                  | 12{% if currentVersion == "enterprise-server@2.22" %}<br/>or [**16**](#beta-features-in-github-enterprise-server-222){% endif %} |                                                                                                                                          96 GB |                                                                                                                                         750 GB |       200 GB |
| 8,000 to 10,000+               | 16{% if currentVersion == "enterprise-server@2.22" %}<br/>or [**20**](#beta-features-in-github-enterprise-server-222){% endif %} | 128 GB{% if currentVersion == "enterprise-server@2.22" %}<br/>or [**160 GB**](#beta-features-in-github-enterprise-server-222){% endif %} |                                                                                                                                        1000 GB |       200 GB |

For more information about adjusting resources for an existing instance, see "[Increasing storage capacity](/enterprise/admin/installation/increasing-storage-capacity)" and "[Increasing CPU or memory resources](/enterprise/admin/installation/increasing-cpu-or-memory-resources)."

{% if currentVersion == "enterprise-server@2.22" %}

#### Beta features in {% data variables.product.prodname_ghe_server %} 2.22

You can sign up for beta features available in {% data variables.product.prodname_ghe_server %} 2.22 such as {% data variables.product.prodname_actions %}, {% data variables.product.prodname_registry %}, and {% data variables.product.prodname_code_scanning %}. For more information, see the [release notes for the 2.22 series](https://enterprise.github.com/releases/series/2.22#release-2.22.0) on the {% data variables.product.prodname_enterprise %} website.

If you enable beta features for {% data variables.product.prodname_ghe_server %} 2.22, your instance requires additional hardware resources. For more information, see "[Minimum requirements](#minimum-requirements)".

{% endif %}
