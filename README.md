# Andriod-APP
why hybrid app is more popular now?

Abstract


Since IOS and Android are taking the most mobile device market, App is getting
popular. Developers know that there are two general types of App. One is Web app
which runs on browser and the other one is local APP which runs on mobile device.
Native App is developed for particular mobile system and it has fast reaction speed. It
also needs high investment of the talented and time to be accomplished. In terms of
hybrid App, it has half web and half native development which can be applied on
multiple systems. This is a new model and it does not have mature technology
therefore the user experience is not really excellent. Currently, HTML5 and cordova
play an important role in mobile application development because they make anularJS
and ionic technology available on mobile devices. This also helps hybrid App
becomes popular in App development model because they bring decent dynamic
effects to phones. For companies, it is necessary to spend money on key points and
hybrid App needs low investment that is why hybrid App becomes popular. This
report will introduce what are native and hybrid App in the beginning. The following
content will explain the benefits and drawbacks in details that these two app
development have based on two App projects that I was involved in NeuqSoft.
Although hybrid model is not really mature in some part, I believe that it will take the
market because it can bring more benefits to company than native model.


Introduction


Native App is the traditional developing App model. For the particular running system
such as IOS and Android, this model needs developers to apply different
programming languages and framework on. Java is the main language of
programming for Android native App. In terms of iOS native App, it is mostly used
Object-C/Swift.Native App is mostly designed for one type mobile device. It is
directly installed into the device so does its UI components, database and logic
framework. Most of them are available in App store and Android Apps on Google
Play. The use of the API is provided by the official development therefore App has
smooth performance experience with a small amount of CPU and memory overhead.
In addition, native development model can achieve cooler effects, better compatibility
and greater user experience than hybrid model.

Hybrid App applies half native and half HTML5 development model. Its bottom
function API is built by native containers and the logical functions is finished through
HTML5. That is why hybrid App is famous as being intervenient from web App and
native App. The most Apps that are famous in China are hybrid such as the hot
Chinese online shopping App TaoBao. The diagram below shows how JSBridge plays
important role in hybrid App development.


This diagram also illustrates that hybrid development can build two vision iOS and
Android at the same time. There is an option to ask the developers which version do
they want or both of them. This is a great advantage that native App cannot achieve.
JS is the crucial part of hybrid app development because it is the main tool to achieve
the most function such as refreshing pages, downloading attachment, loading
information and changing password ect. Hybrid App becomes popular and this
development model is applied in a lot Apps. It can achieve complicated logic with few
code and require low investment. This is new model and it is still not as consummate
as native development model. Native App brings great user experience and flash
interaction which causes a lot extra work. The current App market cares about the
benefit which is the great advantage of hybrid APP. I believe that hybrid App will take
most market based on the listed advantages.
Native
HTML5 page
JSBridge
Android iOS


Analysis


OA office system APP- my hybrid project
OA stands for office automation. OA office system changes the traditional document
processing way from handwriting to online marking. It solves the low working
efficiency problem and makes all the comments clear to every staff who is involved.
This App also reduces the troubles of losing document pages and delaying of auditing.
The project that I was doing is OA office system for gov of the xxx city. ( My
supervisor asked to do not show the city name because the confidential problem.
Thanks for the understanding) In term of its development platform, OA office system
App is mainly developed on WeX5 which is a great platform for hybrid App.
WeX5 follows Apache free source protocol and it is hundreds of framework
components such as frame assembly visualization, integration of third party
components, using the MVC design pattern, the data and view the separation,
separation of page description and code logic, supporting browser debugging, device
debugging, debugging and other native debugging are all available to developers.
Users can also get the original code of this model. Wex5 has insisted on the use of
H5+CSS3+JS technology which provides multiple versions for one-time development.
The hybrid App development model of Wex5 can easily call the function on mobile
for instance cameras, maps, contacts, etc. This is really convenient for developer deal

with complex data applications and it is possible to reduce 80% of the code. It not
only decreases the working quantity but also makes the developing process clear.
The work of developing OA office system App can be divided into three big parts
which are UI designing, loading and searching data and achieving the official process
of approving documents in the government into App. UI designers need to give the
plan of 5 lists and 8 details pages. The 5 page list contains a to-do list, finished list,
notification list, query data list and statistical process monitoring list. 8 details page to
be included in bureau issued documents details page, bureau accepted documents
history page, department accepted documents history page, department issued a
documents details page, informal document details page, information reporting page,
process monitoring details page and the personal information page. The first 6 pages
has similar designed style. All the listed branches are applied HTML5 code to set up
the control framework and CSS to adjust style and dynamic effect.
How to deal with complicated conditional statement in OA office system App
The entire logical diagram is too complicated to be shown therefore I pick one
branch( Accepted document history) to simply explain the logic. The diagram below
is how does internal branch work and connect.


Logic flow chart of OA office system App

The diagram shows that Accepted document history has a lot conditions which will
cause a lot works. From the diagram, it is clear to see that both heading directors in
public institution and related department need to review the application to pass it. The
left side show the process of how public institution reviews the application document.
If High level director approves the application, the related staff will process document
will to be accepted . Otherwise, the application will be reviewed by other directors
before it is accepted. In terms of the responsible department part, there are three ways
to review application file. The first one is that related staff process it directly without
suggestion form other directors. The second path is that both of them works together
to finish accepting document.It is also fine that director accepted the application file
without reviewing from other staff. It is obvoicse that there are so many conditional
statement need to be handle and these are only a small apart of the entire App.
Theoretically, switch statement fits this kind plenty conditional statement well . To
achieve the above logic, the team proposed to ‘if’ statement in the end. Although too
much nested if condition possibly makes code mass, merging ‘if’ and ‘switch’ will
make the code unreadable. Since there are many staffs can read application documents,
it might cause secrets leaking out. Therefore, the auditing part is initialized to be
partly invisible. For different level of users, this part will illustrate different level of
content because the confidential problem. This logic projects the heading file safety
and heading staff information.



Dynamic effect challenge of hybrid development model

In the system, there are many modules have similar UI design such as every list page.
Therefore, there is a main CSS document that controls those similar pages. In the
actual programming, there are some typical problems such as distortion of inserted
icons, absence of front and not fitted characters. OA office system App is applied
hybrid development model and its framework is built by HTML5 which has
unavoidable particularity. This layout believes that inserted icons inevitably need to
zoom and extend therefore inserted icons are easily distorted and their location are
hard to be fixed. For this problem, my team decides that to use icons from Wex5
instead of designed icon. In the fact, Wex5 is an quirt mature hybrid development
platform and it is professional on developing office Apps. Great office icon library
that Wex5 has helped the team to decide to apply all Wex5 icons in OA office system
App. It perfectly avoid icon distortion and system icon fits really well with the page.
Since the compatibility of inserted icons is not as comparative as system icons, all
icons in OA office system App are from Wex5 system. In terms the problem of front, I
am not the only developer who are programming for the App and Wex5 does not
provide specific options for front size. When the director combined everyone’s branch
together, everybody has different front and size which looks messy. UI department
picked the best fitted front, size and color for this App. All the setting is updated in the
main CSS document to solve this case. Hybrid App is usually programmed on
third-party cross-platform mobile application engine framework and OA office
system App uses Wex5. Since hybrid development is new and some development tool
might has bug in the system which causes the trouble for developers.


Wex5 has specific model which might have conflict with what developers wants to
show. The client requires that each list page title displays two lines and the extra
characters should be shown as ellipsis. However, the team does not find a proper
character strategy to fit every mobile device screen of this character requirement. The
team finally decided to only fit the currently most popular mobile devices. According
to these 3 selected screen size, the team calculated the best fitted number of characters
therefore it can makes the extra characters to ellipsis. There is another trouble that can
not be solved because the Wex5 system. It is possible that the tile will has number and
punctuation which has different width with mandarin. It causes a little distortion .
Since it is considered as a bug of Wex5 and it is not really obvious, this problem is not
solved.


X job finder APP -my native App project.


Native App development needs more people and more time than hybrid App
development. X job finder App is programmed on eclipse·ADT and Android Studio
which are Android development tools. X actually stands for one city name but it is not
allowed to be shown in terms of confidential problem. This X job finder APP is
designed to provide jobs opportunities in local and surrounding area of X city.
Currently, it is only available of Android version and it is applied native development.
The home pages of X job finder APP is the center searching page where clearly
illustrates posted job information and different job types ect. In the advanced search
part, it can provide exact job opportunities according to the input requirement of
education, job location, salary and so on. X job finder App can provide the official
data of what kind position is popular from service center in the government and it also
allows user to modify their uploaded resume. It also can send the best fitted position
to user through specific calculating algorithm based on where user want to work, what
kind job is their favorite and how much salary is accepted by them. If user submits
application to one position, he can also see whether it is approved, when did HR read
his resume and when he will have interview. The listed are only part of the whole
function and some details will be introduced as well.


X job finder APP brings mobile service to user which means users can see the posted
job information everywhere instead of using PC in office. It is a great function not
only for people who are looking for jobs but also for HR. In addition, this App also
brings the service of conversation between employee and employers which can be
consider as a quick test for user to know whether they fit this job well. Why X job
finder APP is wanted since there are some famous job finding Apps in China already
such as 51 job, ganji.com and Lietou.com? Most existing job finding Apps provide
job opportunities towards to the entire country which might make them too general. X
job finder APP concentrates on X city and the surroundings which can collect more
exact information and more details than other similar Apps.


Native App brings cool flash effect

Information providing App should be able to load plenty of data and process complex
logic. X job finder App needs to illustrate posted job information as much as possible
with limited page space. In the native App development, this is where ListView
(RecyclerView) comes in handy. RecyclerView can substitute ListView. It is more
functional and has better scalability than ListView. ListView (RecyclerView) is quite
mature on performance of plenty data through reducing creating View and applying
only visible view to save memory and CPU overhead. ListView (RecyclerView) can
show four different views of the project such as big(standard) icon, small icon, list
and table. It also can decrease the number of sending request to save memory and
CPU overhead through using cache. The below picture is the home page of X finder
APP which the my team applied the above structure.
Home page of X job finder App


It view list in the middle to show the opportunity trend, notification, salary, service
list, resume, job application, interview arrangement and collected job. The top
searching block provides position searching result and it also has advanced search
which is mentioned before. The following rolling part is the real-time jobs
information which includes simple description and the salary. Its nav in the bottom to
assist users to quickly get into home page, collected jobs, system massage and
personal information. The below picture is UI design of OA App and it is illustrated
for comparing the visual experience of these two App.
UI design of OA office system App


These pictures can also tell that X job finders App brings better flash effect, brighter
color and more clear structure than OA office system App. Comparing with hybrid
development, native development is much more mature than it on function optimizing.
For example, X job finder App uses dynamic effects in the page switching, data
loading and picture display ect. Native development can strong API to support
dynamic effects. Abundant API highly fits the system which brings fast response
speed, comfortable visual effects and user-friendly experience.In hybrid development,
its graphics rendering and dynamic effects are dependent on GPU acceleration. The
current GPU on PC is much greater than the one on mobile device therefore hybrid
App has common dynamic effects on mobile device. Although hybrid App have
fluent flash effect when it runs on browser, most users use local Apps on mobile
device.To achieve same effect, hybrid development will cause a lot of memory
consumption. Hybrid App also needs high level mobile equipment, otherwise it will
cause paused, flashback and crash problems. This is still a great advantage of native
App because it needs long time and high technical logic for hybrid App development
software to achieve as cool flash effect as native App. The below picture is UI design
of OA App and it is illustrated for comparing the visual experience of these two App.
Cool dynamic effects require a lot investment


Native App brings great dynamic effects to users but it needs more investment. X job
finder App has been programmed by a team of 5 developers for one month. OA has 8
people but it only took one week. Currently, X job finder App is only available for
Android version. If the market shows demand of iOS version, developers needs to
reprogram the entire App. In terms of updating, native App needs to update two
versions which can be consider as updating two different APP. For this problem,
hybrid development model seems much cheaper than native development model.
Hybrid App development tools such as Wex5 can produce two version App from one
program. When it is necessary to update App, it can update for multiple versions at
the same time which saves a lot work.



Conclusion:

In summary, it is hard to tell which type model is better than another one. There might
not be enough data for illustrating the current Chinses software market but it is
common to see hybrid Apps are everywhere. I believe that the function of App and the
market decide which kind model will be applied. If the wanted App needs to have
fantasy effect, GPS location and complex communication, native App is a great
choice because these functions require high UI/UX technique. Additionally, the
drawbacks will not have bad influence in the future on hybrid development since
HTML5 and cordova already have improved a lot the the dynamic effect on hybrid
App. This report is not saying that native development will be replaced and I wish that
this model will develop well in the future as well. Combining with the current market,
benefits plays really important role and the trend of hybrid is super popular therefore I
have my own conclusion that hybrid will take the market.
18
Reference:
1. Diagram 1: http://www.cnblogs.com/dailc/p/5930231.html
2. Wex5 official web: http://www.wex5.com/wex5/
3. Three internal documents
