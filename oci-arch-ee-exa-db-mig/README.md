# oci-arch-ee-exa-db-mig

This code will help you deploy a compute instance and Exadata Cloud Service (Quarter Rack) database system in Oracle Cloud Infrastructure.

## How this project is organized

The terraform code will deploy a VCN, a 4 OCPU compute instance in a private subnet and Exadata Cloud Service (Quarter Rack) database system. There will be a private subnet attached to the Exadata database system for client traffic and another one for backup traffic.


## Prerequisites

First off we'll need to do some pre deploy setup.  That's all detailed [here](https://github.com/oracle/oci-quickstart-prerequisites).

## License

You may not use the identified files except in compliance with the Apache License, Version 2.0 (the "License.")

You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0. A copy of the license is also reproduced in LICENSE.md

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

See the License for the specific language governing permissions and limitations under the License.

