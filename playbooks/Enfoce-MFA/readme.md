This playbook will take user(s) from Sentinel alert and move then to a specified Azure AD group to enforce MFA on those users. First you need to create the group, then create a new Azure AD Conditional Access policy that enforces MFA for the group. During deployment of this playbook, you need to have groupid of the group.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fluberan%2FSentinel%2Fmaster%2Fplaybooks%2FEnfoce-MFA%2Fazuredeploy.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton""/>
</a>
