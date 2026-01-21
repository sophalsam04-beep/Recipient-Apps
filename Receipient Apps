import 'package:flutter/material.dart';

void main(List<String> args) {
  runApp(const App());
}

class App extends StatelessWidget {
  const App({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      home: const HomeScreen(),
    );
  }
}

class HomeScreen extends StatefulWidget {
  const HomeScreen({super.key});

  @override
  State<HomeScreen> createState() => _HomeScreenState();
}

class _HomeScreenState extends State<HomeScreen> {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      backgroundColor: Colors.grey.shade100,
      appBar: AppBar(
        elevation: 0,
        backgroundColor: Colors.white,
        leading: const Icon(
          Icons.menu,
          size: 30,
          color: Colors.black,
          fontWeight: FontWeight.bold,
        ),

        actions: const [
          Padding(
            padding: const EdgeInsets.only(right: 16),
            child: Icon(
              Icons.notifications_none,
              size: 30,
              color: Colors.black,
              fontWeight: FontWeight.bold,
            ),
          ),
        ],
      ),
      body: SingleChildScrollView(
        padding: const EdgeInsets.all(16),
        child: Column(
          crossAxisAlignment: CrossAxisAlignment.start,
          children: [
            Container(
              decoration: BoxDecoration(
                borderRadius: BorderRadius.circular(20.0),
                color: Colors.green,
              ),
              padding: const EdgeInsets.all(20),
              child: Column(
                crossAxisAlignment: CrossAxisAlignment.start,
                children: [
                  CircleAvatar(
                    radius: 30,
                    child: IconButton(
                      onPressed: () {},
                      icon: Icon(
                        Icons.data_thresholding,
                        size: 30,
                        color: Colors.red,
                      ),
                    ),
                  ),
                  SizedBox(height: 20),
                  Text(
                    "Balance",
                    style: TextStyle(
                      color: Colors.white,
                      fontSize: 18,
                      fontWeight: FontWeight.bold,
                    ),
                  ),
                  const SizedBox(height: 5),
                  Text(
                    "\$544.33",
                    style: TextStyle(
                      color: Colors.red,
                      fontWeight: FontWeight.bold,
                    ),
                  ),

                  Row(
                    mainAxisAlignment: MainAxisAlignment.spaceAround,
                    children: [
                      SizedBox(height: 3),
                      Icon(
                        Icons.incomplete_circle_rounded,
                        size: 30,
                        color: Colors.white,
                      ),
                      Icon(
                        Icons.manage_accounts_rounded,
                        size: 30,
                        color: Colors.white,
                        fontWeight: FontWeight.bold,
                      ),
                      Icon(
                        Icons.arrow_back_ios,
                        size: 30,
                        color: Colors.white,
                        fontWeight: FontWeight.bold,
                      ),
                      Icon(
                        Icons.flutter_dash,
                        size: 30,
                        color: Colors.white,
                        fontWeight: FontWeight.bold,
                      ),
                      Icon(
                        Icons.telegram,
                        size: 30,
                        color: Colors.white,
                        fontWeight: FontWeight.bold,
                      ),
                    ],
                  ),
                ],
              ),
            ),
            Row(
              mainAxisAlignment: MainAxisAlignment.spaceAround,
              children: [
                IconButton(
                  onPressed: () {},
                  icon: Icon(
                    Icons.person,
                    size: 35,
                    color: Colors.red,
                    fontWeight: FontWeight.bold,
                  ),
                ),
                IconButton(
                  onPressed: () {},
                  icon: Icon(
                    Icons.wifi,
                    size: 35,
                    color: Colors.red,
                    fontWeight: FontWeight.bold,
                  ),
                ),
                IconButton(
                  onPressed: () {},
                  icon: Icon(
                    Icons.payment,
                    size: 35,
                    color: Colors.red,
                    fontWeight: FontWeight.bold,
                  ),
                ),
              ],
            ),

            Column(
              mainAxisAlignment: MainAxisAlignment.start,
              children: [
                Text(
                  "Receipient",
                  style: TextStyle(
                    fontSize: 20,
                    color: Colors.green,
                    fontWeight: FontWeight.bold,
                  ),
                ),
                SizedBox(height: 12),
                SizedBox(
                  height: 60,
                  child: ListView.separated(
                    itemBuilder: (_, index) => const CircleAvatar(
                      radius: 28,
                      backgroundColor: Colors.grey,
                      child: Icon(Icons.apple, size: 30, color: Colors.white),
                    ),

                    separatorBuilder: (_, _) => const SizedBox(width: 12),
                    itemCount: 5,
                  ),
                ),
              ],
            ),
            Column(
              crossAxisAlignment: CrossAxisAlignment.start,
              children: [
                Text(
                  "Select Services !",
                  style: TextStyle(
                    color: Colors.purple,
                    fontWeight: FontWeight.bold,
                  ),
                ),
                SizedBox(height: 12),
                GridView.count(
                  crossAxisCount: 4,
                  mainAxisSpacing: 12,
                  crossAxisSpacing: 12,
                  shrinkWrap: true,
                  children: const [
                    Icon(
                      Icons.home,
                      size: 30,
                      color: Colors.orange,
                      fontWeight: FontWeight.bold,
                    ),
                    Icon(
                      Icons.laptop_mac,
                      size: 30,
                      color: Colors.orange,
                      fontWeight: FontWeight.bold,
                    ),
                    Icon(
                      Icons.window,
                      size: 30,
                      color: Colors.orange,
                      fontWeight: FontWeight.bold,
                    ),
                  ],
                ),
              ],
            ),
          ],
        ),
      ),
      bottomNavigationBar: BottomNavigationBar(
        selectedItemColor: Colors.green,
        unselectedItemColor: Colors.grey,
        items: [
          BottomNavigationBarItem(
            icon: Icon(Icons.home, size: 30, color: Colors.black),
            label: "HOME",
          ),
          BottomNavigationBarItem(
            icon: Icon(Icons.bar_chart, size: 30, color: Colors.black),
            label: "Chart",
          ),
          BottomNavigationBarItem(
            icon: Icon(Icons.credit_card, size: 30, color: Colors.black),
            label: "Card",
          ),
          BottomNavigationBarItem(
            icon: Icon(Icons.person, size: 30, color: Colors.black),
            label: "Person",
          ),
        ],
      ),
    );
  }
}

Widget _BalanceCard() {
  return Container(
    padding: const EdgeInsets.all(25),
    decoration: BoxDecoration(
      borderRadius: BorderRadius.circular(30.0),
      color: Colors.green,
    ),
    child: Column(
      crossAxisAlignment: CrossAxisAlignment.start,
      children: [
        const Text(
          "Balance",
          style: TextStyle(
            fontSize: 15,
            fontWeight: FontWeight.bold,
            color: Colors.white,
          ),
        ),
        const SizedBox(height: 8),
        const Text(
          "\$ 5455.04",
          style: TextStyle(
            fontSize: 14,
            color: Colors.red,
            fontWeight: FontWeight.bold,
          ),
        ),
        Row(
          mainAxisAlignment: MainAxisAlignment.spaceBetween,
          children: [
            _infoItem(
              title: "InCome",
              value: "\$343.340",
              icon: Icons.arrow_downward,
            ),
            _infoItem(
              title: "Expense",
              value: "\$230.34",
              icon: Icons.arrow_upward,
            ),
          ],
        ),
      ],
    ),
  );
}

Widget _actionButton() {
  return Row(
    mainAxisAlignment: MainAxisAlignment.spaceAround,
    children: [
      ActionItem(icon: Icons.send, label: "Send"),
      ActionItem(icon: Icons.swipe_down, label: "Tranfer"),
      ActionItem(icon: Icons.send, label: "Request"),
      ActionItem(icon: Icons.send, label: "Pay Bill"),
    ],
  );
}

Widget _receipient() {
  return Column(
    mainAxisAlignment: MainAxisAlignment.start,
    children: [
      Row(
        mainAxisAlignment: MainAxisAlignment.spaceBetween,
        children: [
          const Text(
            "Receipt",
            style: TextStyle(fontSize: 15, color: Colors.white),
          ),
          Text(
            "Views All",
            style: TextStyle(
              fontSize: 15,
              color: Colors.white,
              fontWeight: FontWeight.bold,
            ),
          ),
          SizedBox(
            height: 60,
            child: ListView.separated(
              scrollDirection: Axis.horizontal,
              itemBuilder: (_, index) =>
                  const CircleAvatar(radius: 28, backgroundColor: Colors.grey),
              separatorBuilder: (_, _) => const SizedBox(width: 12),

              itemCount: 5,
            ),
          ),
        ],
      ),
    ],
  );
}

Widget _service() {
  return Column(
    crossAxisAlignment: CrossAxisAlignment.start,
    children: [
      Text(
        "Select Servicce !",
        style: TextStyle(fontSize: 15, color: Colors.black),
      ),
      const SizedBox(height: 16),

      GridView.count(
        crossAxisCount: 4,
        mainAxisSpacing: 12,
        crossAxisSpacing: 12,
        shrinkWrap: true,
        physics: const NeverScrollableScrollPhysics(),
        children: const [
          _serviceItem(icon: Icons.home, label: "Home"),
          _serviceItem(icon: Icons.wifi, label: "Home"),
          _serviceItem(
            icon: Icons.phone_bluetooth_speaker_rounded,
            label: "Home",
          ),
          _serviceItem(icon: Icons.phone_android, label: "Home"),
          _serviceItem(icon: Icons.water_drop, label: "Home"),
        ],
      ),
    ],
  );
}

class _infoItem extends StatelessWidget {
  final String title;
  final String value;
  final IconData icon;
  const _infoItem({
    super.key,
    required this.title,
    required this.value,
    required this.icon,
  });

  @override
  Widget build(BuildContext context) {
    return const Placeholder();
  }
}

class ActionItem extends StatelessWidget {
  final IconData icon;
  final String label;
  const ActionItem({super.key, required this.icon, required this.label});

  @override
  Widget build(BuildContext context) {
    return const Placeholder();
  }
}

class _serviceItem extends StatelessWidget {
  final IconData icon;
  final String label;

  const _serviceItem({super.key, required this.icon, required this.label});

  @override
  Widget build(BuildContext context) {
    return const Placeholder();
  }
}
