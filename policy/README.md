## Conjur Policies

Policies define the access structure of your automation environment. Policies scope access to apps, workflows, jobs, services, hosts, layers, or any other unit you may want to define.

Here we have sample policies designed to secure SSH access to common tools such as Oracle, Salt Stack, and Jenkins. We also have policies designed to support specific use cases, like controlling access to Jenkins jobs.

Conjur policies are written in Conjur's DSL2 syntax.

##Organizing Policies

1. Put all policies in the 'policy' directory
2. Organize policies into workflow folders.
3. Policies can be scoped to just about anything -- use cases, applications, jobs, services, hosts, layers, etc.

<img src="https://raw.githubusercontent.com/conjurdemos/enterprise-example/master/policy/policy-info-arch_v3.png" width="300px"/>

##Policy Naming Conventions

1. Avoid extra long folder names and complex hierarchical structures.
2. Use the underscore ( - ) as element delimiter.
3. Elements should be ordered from general to specific detail of importance as much as possible.
4. Dates should be ordered: YEAR, MONTH, DAY. (e.g. YYYYMMDD, YYYYMMDD, YYYYMM).
5. Keep it clean. No need for capitalization. 
