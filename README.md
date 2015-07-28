# ng-splitter
This project is create a splitter layout directive for angularjs

This is a project that create a simple directive to create some basic layout using splitter.
This is extended from @blackgate project (link: https://github.com/blackgate/bg-splitter).

- Create a basic resizable with a collapsed button splitter as the code below:
    <quote>
    <div style="height:99%;">
        <div style="height:100%;">
        <bg-splitter orientation="vertical" position="bottom" unit="px">
            <bg-pane size="250">Pane 1</bg-pane>
            <bg-pane>
                Pane
            </bg-pane>
        </bg-splitter>
        </div>
    </div>
    </quote>
- Create a nestest layout using the code as below:
 <quote>
  <div style="height:99%;">
        <div style="height:100%;">
        <bg-splitter orientation="vertical" position="bottom" unit="px">
            <bg-pane size="250">Pane 1</bg-pane>
            <bg-pane>
                <bg-splitter orientation="horizontal" position="left" unit="px">
                    <bg-pane size="150">Pane 1</bg-pane>
                    <bg-pane >Pane 2</bg-pane>
                </bg-splitter>
            </bg-pane>
        </bg-splitter>
        </div>
    </div>
</quote>
