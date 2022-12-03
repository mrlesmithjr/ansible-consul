commit 9c27eafdde0d5fb673e9c512c7d374afa28ad51f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 09:16:28 2020 -0400

    Added Apt cache_valid_time back

commit 7031c395ff623a8e2246ebe6fd5162143c66ca54
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 02:08:47 2020 -0400

    Added bootstrap-python role as requirement

    This should solve Python requirements issues

commit 22a2f9357febeadcff2c70800dffb38e670d3436
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 02:08:08 2020 -0400

    removed unused requirements

    This is used from repo root so these are not needed

commit b001d632ec240680bd76b38074894af9ca2a4bd0
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 01:19:55 2020 -0400

    Updated Galaxy platforms

commit 636f768953f10b30907c6169ef2e402283c369f3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 01:18:17 2020 -0400

    Disabled CI testing for Ubuntu1604

    Idempotency fails on apt cache update same as Debian8

commit df9480881f5454782414ab3e46eef26baad06e8c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 00:53:56 2020 -0400

    Trying to fix CentOS7 Python Packages

commit 954daa7270ba2a2abb52ffe075f7bd129bf80c09
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 00:29:54 2020 -0400

    Changing package pre-reqs to simplify

    Will troubleshoot after failures

commit d40831955c93ff2116f251f410d4ff0eceb3fe54
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 00:16:32 2020 -0400

    Fixing CentOS7 Python Packages

commit 9a63a367c807538d3382ad5acb8ecd5384725560
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 23:56:14 2020 -0400

    Fixed Python packages for RedHat

commit 62a862dceffe8cb633de5be7a1bef1ef8c271d33
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 23:33:51 2020 -0400

    Added missing consul_servers group for Molecule Ubuntu2004

commit ee89255f1eee6b4693f6922e55b08b4efb3bd6fc
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 23:19:01 2020 -0400

    Updated to latest Cookiecutter template

commit f1f8fdc1bda4492d70d3d877914cd98b1b37e2ec
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 22:49:10 2020 -0400

    Updated info about new Consul client role

commit 7570df7eb7f9e21ce23ded5e5dc8a35e47fcf58a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 22:29:06 2020 -0400

    Testing different Travis tests

commit 5dad21c3102a422ad2a12a5075e77be40617509f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 22:12:59 2020 -0400

    Adding Python requirements back to workflow

commit 67a76e4fdee64e440bb3122ea04b7b566e9fa29c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 22:08:59 2020 -0400

    Testing another way for Actions

commit 5a905a18e50bd8904c1182766859b81a5f3c21a3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 22:06:50 2020 -0400

    Testing different GitHub Actions workflow

commit 97d0340a933e41f13368e588037c3977a1429e40
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 21:42:46 2020 -0400

    Fixed Python package installs

    Need to ensure we are installing Python3 packages and setuptools

commit c61b509e45fe1978eb458d8dbf616a58841e7833
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 20:32:12 2020 -0400

    Removed client services functionality

    This functionality will be moving to https://github.com/mrlesmithjr/ansible-consul-client

commit 2d3c27ba3129c391c56ed83b2d255a510619fde3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 20:04:27 2020 -0400

    Updated CI tests to most current

commit 067f75426c83b08ed419700af90155eae3a8c9a5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 19:55:35 2020 -0400

    Fixed issue with consul_acl loop

    New loop|subelements causing issues with previous definitions

commit 9e41616c432e9b2b8b59c6539a2a463e6de50269
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 19:40:41 2020 -0400

    Cleaned up loops

    - Changed with_items to loop
    - Changed with_subelements to loop

commit c74c03b43df7276f1c70f4504562e9ab84d94c98
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 19:36:36 2020 -0400

    Cleaned up formatting of pip installs

commit 2b8f9c0308f18c04c0b862ccf1f2d1cf658d9058
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 19:31:15 2020 -0400

    Removed tags

    Need to minimize the usage of tags until absolutely needed

commit 016a4af848f09478436daf495709f78b6f5f9b83
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 19:30:11 2020 -0400

    Simplified Consul install task(s)

commit fcc0b1c3192a9f906ac6d1d937f7768e1de6c29d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 19:29:37 2020 -0400

    Removed set_facts tasks

commit c48906a6163911de3a0154127975a3091f934a5e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 19:28:50 2020 -0400

    Cleaned up package installs

    - Consolidated where applicable
    - Cleaned up formatting where applicable

commit 5fc083a6e93247662a7126a782643db5dbb89bd7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 19:27:48 2020 -0400

    Tightened up Consul user account

commit b4b7b56e7d1f8e5070112c0650803f2e5c3041fc
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 19:27:26 2020 -0400

    Cleaned up when conditions

    The previous conditions needed to be cleaned up badly.
    We need to ensure our conditionals are as simple as possible.

commit 241b6a337e7f5a1226160dae474567e18ef9accc
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 19:10:02 2020 -0400

    Updated Python requirements

    Updated Python requirements for testing, etc. including Molecule

commit 8d450cee7714d25c2156fb3912a2d28fcaa70369
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 19:09:00 2020 -0400

    First major variable refactoring

    Switching to a consolidated configuration option which is converted to JSON
    This brings the configuration of Consul in sync with our other Hashi roles

commit d9cf9f48a3e5edc374b109cecbc3034768f56fcd
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 14:42:34 2020 -0400

    Added Apt cache update for Debian

    Need to ensure that all package info is up to date

commit bb7d905c894b6c76218be14c4f9904745e9e2b3f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 14:15:05 2020 -0400

    Changed logic for consul_bind_address

commit 75c31d51dd3c0c68b77999c8cfa4dc0206efb4aa
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 16 13:34:12 2020 -0400

    Cleaned up unused handlers

commit edcf0decb386e4d67541578f8dfc4519d65f0b31
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Apr 7 16:47:02 2020 -0400

    Upgraded Consul version to latest

commit b8eb5eaf88a2c068072469b9300af0e91858e70b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Apr 7 16:30:55 2020 -0400

    Fixed conditionals, etc. from failed tests

commit d9472068496b421aa1eef3ed2e05c3a94b4d4b7f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Apr 7 16:30:09 2020 -0400

    Added Consul group for testing

commit beeefd6a5f794e29e13b9dacc66a53975d800f95
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Apr 7 16:08:19 2020 -0400

    Fixed linting issues

commit 3042853ed573dd8322a2a73dca7f28ce0d999437
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Apr 7 15:51:16 2020 -0400

    Added: New files, etc. from cookiecutter template

commit cccc4cf42d004a749002b37cbf6cb1a7fb885bee
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Apr 7 15:51:04 2020 -0400

    Updated files, etc. after new structure

    This aligns to cookiecutter template

commit eb63bddc88f42c4499f59019f93fbe537b206366
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Apr 7 15:46:37 2020 -0400

    Deleted old tests, etc. not needed

    These files are no longer required for new format

commit f082995a05e669223f67e2c6280a4d1e1b8411c5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Dec 27 21:40:20 2018 -0500

    Disabled actual execution as we need a cluster IP and containers do not allow this for testing

commit 870b221327da25804ada1b00f1597ee820e49f1e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Dec 27 21:34:14 2018 -0500

    First commit of refactoring

    Cleaned up code based on Ansible lint and YAML lint
    Implemented updated Travis CI testing

commit d31f954700ccda8dc0ad25646ee6b7a5cadc4a51
Author: Manuel Gauto <gauto.manuel@solute.us>
Date:   Tue Feb 6 12:27:41 2018 -0500

    Fix 'Not Fedora' add'l dependencies play in redhat install so they run.

commit 6f0a13ac531e54cd3b66b3e9de312afe1f48673f
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Wed Nov 22 17:17:19 2017 +0100

    allow user to define custom retry-join array

commit da89c83f1352f7e5171525ce2617696a938e35de
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Fri Nov 17 08:29:01 2017 +0100

    removed various disabled/unused lines in playbooks

commit 50cefe9b64a5d01b428b219181182477661bee58
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Fri Nov 17 08:26:30 2017 +0100

    port include to import_tasks in main.yml

commit 01aa3c9a0e3e2eb6f91575b3f069191abcfc5c06
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Fri Nov 17 08:25:46 2017 +0100

    retire standalone.yml incl. consul_cluster switch as it was never used/finished

commit 8671c822b40502400f42d716ee54eb27021813da
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Mon Nov 6 16:43:12 2017 +0100

    added optional deployment of a pre-populates peers.json for outage recovery

    added missing peers.json_prepared.j2

commit 9c403def63d852279a740141c25481db41b83311
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Tue Oct 24 09:00:58 2017 +0200

    sort list consul_retry_join_wan to avoid config change on each role run

commit 2d4b370fb29619e5db839168bb9b59f8f134012d
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Mon Oct 23 15:48:35 2017 +0200

    allow user to configure consul_bind_address based on consul_bind_interface

commit 31ec1a3b48e5f7f33de2a46b21fbfbeeccc0bd7e
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Fri Oct 13 09:01:19 2017 +0200

    removed unused consul_key_file variable

commit 8ff8a1aba7d3cb0aa68b84725d3d26a8eaac3057
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Fri Oct 13 08:13:26 2017 +0200

    added comment about purging consul_retry_join_wan for the target datacenter again

commit 2d5f5887ecd2ea7cc9832f649521075a365eee7d
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Fri Oct 13 08:10:32 2017 +0200

    ensure retry_join_wan is only set on servers

commit 6bb6e2b6ee08f1adb88017830156bb99a6753b7c
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Wed Oct 11 14:25:24 2017 +0200

    added retry-join-wan option to join a existing federation setup

commit b1d3f11bf621e8acf69fa24833699e3b5a5fdee1
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Wed Oct 11 12:58:21 2017 +0200

    removed sleep from services to fix deprecation warning on systemd systems

commit f7cee0e66b444b1a33a22a6dfcb02607f7b34dda
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Wed Oct 11 11:38:08 2017 +0200

    supress logging of tokens passed to consul_acl

commit 8a4710e11f0dc1641874b4089be7de003921cb78
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Thu Sep 21 16:31:32 2017 +0200

    made acl_agent_master_token, acl_agent_token, and acl_token configurable

commit 94e4b85337bf43054a9e5aafdb4173b76f17cf5b
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Mon Sep 11 15:58:38 2017 +0200

    set acl_default_policy only on servers as documented

commit 13257b0c3a6841dd6d6edd5a18e3ab5389a6c6f5
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Tue Sep 12 13:31:47 2017 +0200

    enhanced comments in defaults and README.md on consul_acl

commit 38f8ff536f96aba04c7ae430c3a21f3e2e78855f
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Tue Sep 12 13:31:11 2017 +0200

    include consul-acl only on consul_acl_datacenter as it acts as ACL source

commit 5265da7953b1365247282a238fcf0d4bee5729ad
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Tue Sep 12 13:30:33 2017 +0200

    run consul_acl task only once as this is suffcient to set ACLs globally

commit 08234d3af4094c650c5158d48a87d4113e8a81b7
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Tue Sep 12 13:30:01 2017 +0200

    install required software to set ACLs and allow skipping of these tasks

commit b5eec7139728bd7e1bf7a7df213acfc6a7c2a98e
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Tue Sep 12 11:06:55 2017 +0200

    provide some examples and defaults for consul_acl

commit e2ac08a574a2e546978d4f56d37989b65ee64074
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Tue Sep 12 11:06:42 2017 +0200

    made rules setup in consul_acl working

commit 443d7a7a8d0481c53950c38663f306142ac9b951
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Tue Sep 12 09:03:23 2017 +0200

    enhance condition on acl.yml include

commit d6da893ba596d9a045ecd8239097575a16c1505c
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Fri Sep 8 14:49:32 2017 +0200

    first draft to add consul_acl to role

commit 3e2d2ee6f7dba9bf9265849c69de5667f558c7b9
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Thu Sep 7 11:30:19 2017 +0200

    added ACL replication options

commit eb7f573928ef22c8a66994ed3eb604879686d995
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Mon Sep 4 10:51:26 2017 +0200

    allow user to configure enable_syslog and log_level

commit 2811f189b477d33ebc17adee5b1ec4effa3d67c9
Author: jardleex <jardleex@users.noreply.github.com>
Date:   Fri Sep 1 19:25:55 2017 +0200

    replace dashes with underlines in NIC names as variables/facts must not contain dashes

commit 7300271171566ac683af347fa3fbde7ac8929ebe
Author: Robert Hecht <rohe@spreadshirt.net>
Date:   Fri Aug 25 12:22:27 2017 +0200

    added optional performance config dict

commit 1001dd405c25091acfbcf631c2e5f129ee8c2bc5
Author: Robert Hecht <rohe@spreadshirt.net>
Date:   Thu Aug 24 08:38:32 2017 +0200

    added optional dns_config dict

commit 0f9402b6e38426ca1a08e4b840871249f04fcd75
Author: jardleex <stuff@herob.de>
Date:   Fri Aug 11 08:47:08 2017 +0200

    align consul_version with current master branch

commit 3bd604bc5ce6cb0167efdd56613ea831c022e8b7
Author: jardleex <stuff@herob.de>
Date:   Fri Aug 11 08:39:58 2017 +0200

    enhanced hint on consul_upgrade regarding --forks option

commit 81cfdca9b2a103c1ab04669a952e4d2069d9a10d
Author: jardleex <stuff@herob.de>
Date:   Fri Aug 4 14:53:26 2017 +0200

    added consul_acl_datacenter to allow wan clustered setups with one trust source

commit 49773a1ddde6df19e454516484570da7da90f0cb
Author: jardleex <stuff@herob.de>
Date:   Fri Aug 4 14:42:00 2017 +0200

    raised default consul_version to 0.9.0

commit be15851d91118dd650cb46da00f868739787a283
Author: jardleex <stuff@herob.de>
Date:   Fri Aug 4 14:41:33 2017 +0200

    removed stale consul_acl_master_token_file variable and file

commit 017a2a173bb2e704273c6516abf7dd0b6627e7bd
Author: jardleex <stuff@herob.de>
Date:   Fri Aug 4 14:36:27 2017 +0200

    equalize README.md with defaults.yml on consul_acl_master_token

commit daeb12b9c809c67b30edb6ddd966c9261b8094af
Author: jardleex <stuff@herob.de>
Date:   Fri Aug 4 14:35:44 2017 +0200

    hardstyle simplification of consul_acl_master_token setup

commit 1d321ad9664c0a96718e8babb9cd569c7d7e3c53
Author: jardleex <stuff@herob.de>
Date:   Fri Aug 4 13:14:40 2017 +0200

    set acl_master_token only on servers

commit 8a47da93e14a2ea1405ee160db8d6fc5238c48de
Author: jardleex <stuff@herob.de>
Date:   Fri Aug 4 12:36:09 2017 +0200

    added some become switched to align with common role coding style

commit 1ad99d3015481014285ce27c6f00e50acf120efd
Author: jardleex <stuff@herob.de>
Date:   Fri Aug 4 12:35:48 2017 +0200

    made version detecion, backup/restore more robust

commit 511ba96930514e53f18dd6481fa65dc35b5175e3
Author: jardleex <stuff@herob.de>
Date:   Fri Aug 4 09:20:49 2017 +0200

    added --forks recommendation on consul_upgrade to minimize cluster impact of upgrade run

commit 779bdae006c31380eeadcee9a29d8dea9928fb94
Author: jardleex <stuff@herob.de>
Date:   Fri Aug 4 09:19:01 2017 +0200

    use shell to determine consul version as we need pipes to work

commit a2043b1f5e0542904aa3801dc9b9499139764c1c
Author: jardleex <stuff@herob.de>
Date:   Thu Aug 3 13:13:31 2017 +0200

    reset correct consul_dl_url, accidently commited test setting

commit b7efc9415aaf8600297d62a1c018b3d58edc5a60
Author: jardleex <stuff@herob.de>
Date:   Thu Aug 3 13:11:06 2017 +0200

    enhanced role with consul version upgrade ability

commit 34b331cb93fe1e8d097f8e4cec79912ba87331f7
Author: jardleex <stuff@herob.de>
Date:   Thu Jun 29 20:02:19 2017 +0200

    allow user to rewrite node_name representing node in cluster

commit 7b218aa65a3f85b7e36642cbb511b1e1a023c3d4
Author: jardleex <stuff@herob.de>
Date:   Mon Jun 26 13:42:01 2017 +0200

    added optional telemetry configuration

commit 10acd38c824cfc4c4728326a69476e5d5cb0773f
Author: jardleex <stuff@herob.de>
Date:   Tue Jun 20 15:53:36 2017 +0200

    deleted orphaned consul.key.j2

commit 45c36ee7ebd7f86c3f2b7b7a0a6ccfabb479d514
Author: jardleex <stuff@herob.de>
Date:   Sat Jun 17 15:36:12 2017 +0200

    replace json_query with simple first filter

commit f925b6d61910c4286dc1755b9da17468944f1909
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue May 16 10:42:33 2017 -0400

    Added become: true for generating key... Addresses issue #33

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit be3baa8f07d9f3b63731a603eed37eeb9da7444b
Author: jardleex <rohe@spreadshirt.net>
Date:   Tue May 16 09:15:09 2017 +0200

    create user and group before binary installation

commit e7b3baa36075ec723b6b190bb8b26617939b5602
Author: jardleex <stuff@herob.de>
Date:   Sun May 14 08:58:53 2017 +0200

    added become statement to encryption tasks

commit ea2e5b2d7abf5166847f975c64cf338b2e5a244a
Author: Robert Hecht <mail@herob.de>
Date:   Sun May 14 08:52:25 2017 +0200

    added become and when to reload systemd to ensure sufficient permissions and working tests

commit ebfa0c18c4cacf031247a31b2f74659ab6f7efdb
Author: jardleex <rohe@spreadshirt.net>
Date:   Fri May 12 14:32:25 2017 +0200

    fix travis test

commit cdaa9bd46c23cf3f4ff5bb23973460b096a4b40f
Author: jardleex <rohe@spreadshirt.net>
Date:   Fri May 12 14:25:08 2017 +0200

    simplify encryption with static key and added user info about diverging keys

commit 7c21feffe18f2dc1472c736705b1b6ec1d366ea7
Author: jardleex <rohe@spreadshirt.net>
Date:   Wed May 10 10:03:12 2017 +0200

    set default group and owner of consul binary to consul_user/group, can be overwritten

commit b4394beea0bb34c49f9a9b1df643a26cf4831d4d
Author: jardleex <rohe@spreadshirt.net>
Date:   Wed May 10 09:45:43 2017 +0200

    added note about consul_runas_user in defaults and README.md

commit aaf9dedc88beb0b1fbe5d1685287166b6807d1f1
Author: jardleex <rohe@spreadshirt.net>
Date:   Wed May 10 09:45:18 2017 +0200

    align README.md with defaults/main.yml

commit be4ad70a964892f03b63a4a2367abeea0a1ee2c8
Author: jardleex <rohe@spreadshirt.net>
Date:   Wed May 10 09:35:27 2017 +0200

    run consul as consul user per default, can be overwritten

commit 07bdf72a1536113f6ae51e53eb0285beb265754c
Author: jardleex <rohe@spreadshirt.net>
Date:   Fri May 5 13:06:16 2017 +0200

    fix broken travis test, change included in #26

commit 5725dfd766abf6d038ea540dabe85d41a015bf21
Author: jardleex <rohe@spreadshirt.net>
Date:   Thu May 4 15:34:44 2017 +0200

    empty consul_services per default, examples moved to playbook.yml

commit deb100f8816424b6233de3a5a0b5048159007bcb
Author: jardleex <rohe@spreadshirt.net>
Date:   Thu May 4 15:12:33 2017 +0200

    retired consul_clients_group

commit 62f2ba874cbc0490d1aa0e6507cacc84a4f08e8e
Author: jardleex <rohe@spreadshirt.net>
Date:   Thu May 4 09:31:55 2017 +0200

    removed unused consul_log_file

commit 7d45ac0f281505a74f13a53670f1b13fce8103fd
Author: jardleex <rohe@spreadshirt.net>
Date:   Thu May 4 09:27:58 2017 +0200

    use single task unarchive to download and install consul

commit 87b783fcb7c16f73c4186a0ea60641343ba187a6
Author: Robert Hecht <rohe@spreadshirt.net>
Date:   Wed May 3 16:16:12 2017 +0200

    fix service.json.j2 like from #14

commit 9d60199395c73e743d910ff1fdaafcfdcaad5bbb
Author: Robert Hecht <rohe@spreadshirt.net>
Date:   Wed May 3 16:15:53 2017 +0200

    fix recursion in Vagrant folder

commit 893b6d7a0cc2bae98aac12568b8124aff36255c4
Author: Robert Hecht <rohe@spreadshirt.net>
Date:   Wed May 3 15:35:08 2017 +0200

    fix issue #14

commit 948c0d734eae8a4164413835bc45d08fdfa87c58
Author: Robert Hecht <rohe@spreadshirt.net>
Date:   Wed May 3 15:14:10 2017 +0200

    use integrated consul ui available in verion >0.7.0

commit 1ce6b58430657754da9d3c8a7ba7b778a7fb50ff
Author: Robert Hecht <mail@herob.de>
Date:   Tue May 2 20:58:29 2017 +0200

    retired bootrap flag and moved fully to bootstrap_expect

commit 261743b12cfd8b01535fd692a5fb76e8ca3658ef
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon May 1 16:26:22 2017 -0400

    Updated roles

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit af17a65777de18f139b4c441252aebd72040e949
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon May 1 11:40:12 2017 -0400

    Added conditional for checking if host is in play_hosts

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 9cb6a90f45c997d234c57337ee243f166cfd23d0
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Apr 28 08:26:29 2017 -0400

    Fixes applied to address issue #14

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit c8b892cc6c7393657c05c774f1d985af0a46ecd4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Apr 23 15:05:49 2017 -0400

    Split out cluster related tasks based on consul_cluster var

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit e327a31970e107a640fcadddfffd777bdcb76749
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Apr 23 12:38:49 2017 -0400

    Split out tasks into separate task files

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 8142d109f65301e69b36ff6cc39b688349006be5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Apr 23 11:28:23 2017 -0400

    Setting Travis to spin up with sudo required

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit dbba55dc7ebb6064c98878f71c100cd26a1eb514
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Apr 23 11:25:28 2017 -0400

    Added become true where needed

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit a7d530963e0710e2208cc320c22be918511c7e46
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Apr 23 10:28:36 2017 -0400

    Adding become where necessary

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 255d51dd9b90b7c0c34c9454e16368b018b17e47
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Apr 23 10:29:46 2017 -0400

    Updated repo info

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 77c9199720c41c5ad2e41849c0db1a30f87a5e2c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Apr 23 10:18:14 2017 -0400

    Changed service definition templating

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit ff88e93ae88ec97818d92634dbe662043bf8ec23
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Apr 22 23:58:07 2017 -0400

    Fixed check mode run

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 2999bec60f1cebe5203996883fca45fc230f95e5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Apr 22 23:46:25 2017 -0400

    Added initial ACL setup, changed process of configuring config.json template

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 03eca6b5b147dbbbff0e6086c145aa671473dacb
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 20 22:53:40 2017 -0400

    Removed hosts file which was in wrong place

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 5c24c0df7ce94a5f82a836e81a5cc95dff93a46b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 20 22:48:49 2017 -0400

    Updated Vagrant info and changed redis check script

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 87aa5059b89699f85fcbd3099a61392b8806e25b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 20 22:24:38 2017 -0400

    Updated Vagrant environment for testing

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 242966c7e1b7892fb7b7fbf7813d5aa0b728de08
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 20 22:21:18 2017 -0400

    Fixed template issue

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit e8aad6b497f094a00b1ceef98e725a3574fd361a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 20 20:20:17 2017 -0400

    Cleaned up code and upgrade Consul version

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 6d08948901751bc2eb4fbe3670f9e00b645610c0
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 20 19:47:42 2017 -0400

    Added Travis testing (#4)

    * Added Travis testing

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

    * Added check mode conditional

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

    * Added consul inventory groups

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

    * Added some vars and checks to correctly run through check mode

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

    * Added check mode conditional

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

    * Fixed with_items and added additional conditional for check mode on app services

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 24a296b9667a39248aa2ec702a59f0768b435f82
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jan 5 16:30:55 2017 -0500

    Fixed bootstrap_expect issue with cluster

    When provisioning out a cluster with more than one manager the cluster goes into a strange state making the cluster unreliable. Removing the division of 2 fixes this issue.

commit 400ae04f10e7b08ca9320acdb6e50fb1b0b054c7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Dec 7 22:18:37 2016 -0500

    Addresses issue #2

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 39ddcb79b19c32c4c9951a452c5bb6d2d6d02a8b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Dec 7 22:15:12 2016 -0500

    Addresses issue #1

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit ac691997f947be6498a3419f335a02121a940e90
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Dec 7 22:12:34 2016 -0500

    Fixed Vagrant environment

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 14422755abe37765bf0b0d10083706bd0496d8d5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Oct 27 21:21:36 2016 -0400

    Updated to fix Vagrant issues

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 954d86cb98eefdd4b90991104e02fcc8d8382bc3
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Sat Mar 5 00:13:20 2016 -0500

    Changed back to Trusty

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 14c6b4dc3d53680ea39c6c90672b22b6479b0fef
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Mar 4 23:54:23 2016 -0500

    Added Fedora 23 support

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 0e9b3e1ffe856f4ddf31c8850bbb7cbc6e2eee96
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Mar 4 22:44:07 2016 -0500

    Added RHEL 7 support

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 9ca2b31b13a9c121bb08954a8f166969f8d5d373
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Mar 4 21:56:32 2016 -0500

    Added DNSMasq support for DNS resolv of consul

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 78d6545656331089f096e79ae1dd81b981d68a94
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Mar 4 21:39:12 2016 -0500

    Added Debian Jessie support

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit e4354b4b9e5bf69c712153eccd6e22276f96b1ec
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Mar 4 20:48:35 2016 -0500

    Updated and working for Ubuntu Trusty

    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 11c75fc637dd15f5f9a1cc911b24f84badbfec22
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Sep 19 00:57:36 2015 -0400

    fixed category

commit ca3c5626aebb74902b020fb7ef8259d02454d09f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Sep 19 00:55:50 2015 -0400

    updated meta

commit 74ecb4b8c04b719f54d03275e560abdc86c6d56b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Sep 19 00:54:56 2015 -0400

    first commit
